POSTGRESQL

Accessing PostgreSQL:

	1. sudo -i -u postgres
	2. psql
	
The above is used to access the psql in the terminal.

SHOW and USE doesnt work here!!

	1. for accesing the specific data base (use) = \c;
	2. for listing the database (show) = \l
	3. for quiting from the terminal = \q
	
For listing all the tables:

	1. \dt

BASIC SQL COMMANDS WHICH WE USE:

<img width="563" height="269" alt="image" src="https://github.com/user-attachments/assets/04e7e5b3-e2ab-458d-acc2-1a5e7562fd54" />

____________________________________________________________________________________________________________________________________
CREATING AND DELETING THE DATABASE:

<img width="396" height="272" alt="image" src="https://github.com/user-attachments/assets/b6f87443-3f86-47c4-b4fd-7a31f985b15a" />

FOR USING THE DATABASE FOR MANUPULATION ;

	1.\c db_name
__________________________________________________________________________________________________________________________________

CREATE AND DELETING THE TABLE:

1.SYNTAX:

<img width="396" height="166" alt="image" src="https://github.com/user-attachments/assets/9790a2e5-ebf1-4df9-8c4a-1e50163d20f0" />


2.EXAMPLE:

<img width="259" height="126" alt="image" src="https://github.com/user-attachments/assets/154b8dd8-02fc-420c-9d62-7fb00a102687" />

_______________________________________________________________________________________________________________________________________
INSERTING THE VALUES INTO THE TABLE:

1.SYNATAX

<img width="259" height="126" alt="image" src="https://github.com/user-attachments/assets/2e27bab1-6b31-4ae1-8072-71d7bc1d9009" />


2.EXAMPLE:

<img width="201" height="126" alt="image" src="https://github.com/user-attachments/assets/fe086a35-0ccd-4251-bd0d-01c646dd2a31" />

DATA TYPE IN USED HERE:
		
<img width="460" height="313" alt="image" src="https://github.com/user-attachments/assets/66487542-a590-45aa-b690-9cf618e0020b" />

CONSTRAINTS:
		
<img width="594" height="405" alt="image" src="https://github.com/user-attachments/assets/b8150a19-5ea8-407f-b1af-38dcdbc5ff7c" />

<img width="594" height="405" alt="image" src="https://github.com/user-attachments/assets/987a12c9-6160-4a21-a720-0c823ae269ff" />

<img width="569" height="368" alt="image" src="https://github.com/user-attachments/assets/71ec950f-073d-4a0e-965b-19558ec8aa76" />
_____________________________________________________________________________________________________________

ALTERING THE TABLE:

SYNTAX

<img width="451" height="374" alt="image" src="https://github.com/user-attachments/assets/aec7eeca-85b2-4ba6-898d-fe194e0be5dd" />

NOTE; IN POSTGRES ADD OR DROP COLOUN_NAME IS USED NOT (ADD OR DROP COLOUM COLOUMN_NAME) IS USED 

WORKING OF ALTER IN THE POSTGRES:

<img width="523" height="499" alt="image" src="https://github.com/user-attachments/assets/292e7b8b-8dcb-4736-a41c-5620b1f24397" />

___________________________________________________________________________________________________________________________________

TRUNCATING THE TABLE:

SCHEMA IN THE TABLE WILL NOT BE DELETED BUT THE ITEMS INSIDE THE TABLE WILL BE DELETED

<img width="388" height="140" alt="image" src="https://github.com/user-attachments/assets/ab785d33-585f-4667-a512-2480a381ffa0" />

____________________________________________________________________________________________________________________________________

SHOWING THE TABLE:

1.SYNTAX

<img width="409" height="211" alt="image" src="https://github.com/user-attachments/assets/4c531a36-1a19-4cf2-a1e6-e99e8ac47b24" />

2.EXAMPLE

<img width="409" height="153" alt="image" src="https://github.com/user-attachments/assets/d76ba75c-933f-43a4-b7f1-2a1f792a89fb" />

______________________________________________________________________________________________________________________________________

DML COMMANDS:

1. INSERT - THIS IS USED FOR INSERTING THE DATA INTO THE TABLE AS MENTIONED ABOVE.

2. SELECT - THIS IS USED FOR SELECTING THE COLOUM AS MENTIONED ABOVE

3. UPDATE - THIS IS USED FOR UPDATING THE VALUES INSIDE THE TABLE

<img width="910" height="679" alt="image" src="https://github.com/user-attachments/assets/471b6e3d-67a1-4e7a-9119-01358a46a74b" />

4. DELETE - THIS IIS USED TO DELETE THE ELEMENT INSIDE THE TABLE

<img width="910" height="679" alt="image" src="https://github.com/user-attachments/assets/6f6761ab-36b2-4e33-9fbc-719d28c9ca87" />

_______________________________________________________________________________________________________________________________________

NORMALISATION:

1 NF - THE MULTIPLE VALUES IN THE SAME SECTION ARE NORMALISED

2 NF - PARTIAL DEPENDENCY IS REMOVED

3 NF - TRANSITIVE DEPENDENCY IS REMOVED

BCNF - THE FUNCTIONAL DEPENDENCY IS REMOVED ( ALWAYS THE LEFT SIDE THAT IS THE DETERMINANT SIDE SHOULD BE A CANDIDATE KEY OR A SUPER KEY)


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d9cfff03-b6a1-472d-85a9-e2519f9e46a0" />

IN THIS IMAGE THE BCNF IS SATISFIED BECAUSE THERE IS NO FUNCTIONAL DEPENDENCY BETWEEN THE COLOUMN.





