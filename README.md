# Phone-Directory
Implementing phone directory features through hashing.

Abstract of Project:
In this Project we will be creating a Phone Directory using the Hash 
Table data Structure.

 Goal--------------------->

Our Goal of this project is to optimise the time complexity of the 
code and make searching, deletion, updation and insertion in record 
as fast as possible. This is done through hash table since amortized 
time complexity for it is O(1) unless all keys will hash to the same 
bracket which is highly unlikely.

 Functions----------------->

The task of this project to implement all functions of phone 
directory:

• Create Record-This method takes details from the user like 
ID, Name and Telephone number and create new 
record in the hash table.

• Display Record- This function is created to display all the 
record of the diary.

• Delete Record- This method takes the key of the record to 
be deleted. Then, it searches in hash table if record id 
matches with the key. Then, that record is deleted.

• Search Record- This method takes the key of the record to 
be searched. Then, it traverses the hash table, if record id 
matches with the key it displays the record detail.

• Update Record- This method takes the key of the record to 
be searched. Then, it traverses the hash table, if record id 
matches with the key then it displays the record detail.
We will be taking ID , NAME and TELEPHONE NUMBER from the client.


We are creating a hash table and inserting records. For deleting, 
searching, or updating an entity, the client ID is asked and on the 
basis of equality operator, details are displayed or processed. If 
the record is not found, then an appropriate message is displayed.
Collision is the major problem in the hashing technique. In Open 
Addressing (closed hashing), all collisions are resolved in the 
prime area i.e., the area that contains all of the home addresses.
When a collision occurs, the prime area addresses are searched 
for an open or unoccupied element using linear probing.
Steps for inserting entities in a hash table: 

• If the location is empty, directly insert the entity. 

• If mapped location is occupied then keep probing until an 
empty slot is found. Once an empty slot is found, insert
the entity.
