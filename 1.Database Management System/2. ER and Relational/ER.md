# Entity Relationship Model 

ER Models are a way to represent the design of database. 
Used before making tables. 

Consits of:
- Entity Set
  - Could be an object with physical existence.
  - Example: Student, Teacher, Course, etc.
- Relationship Set
  - It represents the association between entity types.
  - Example: Student *enrolled in* course
- Attributes
  - Properties which define the entity type

# ER Diagram 

- **Entity Set**
  - Weak Entity Set
   
Representation: Simple and double rectangle respectively 
    
![image](https://user-images.githubusercontent.com/44089458/120808414-ade90e00-c566-11eb-9096-c8de514d03f5.png)

- **Relationship Set**
  - Weak Entity Relation 
  
Representation: Simple diamond and double diamond respectively 

![image](https://user-images.githubusercontent.com/44089458/120808250-82feba00-c566-11eb-94cd-a231fc1f6f2a.png)
 
- **Attributes**

Representation: simple oval 

![image](https://user-images.githubusercontent.com/44089458/120806902-05867a00-c565-11eb-8097-6592c8c8f1ed.png)

  - Key attribute: The attribute which uniquely identifies each entity in the entity set. Eg: roll no. 

  Representation: An oval with underlying lines. 
  
  ![image](https://user-images.githubusercontent.com/44089458/120807425-8e9db100-c565-11eb-9591-166fecd0de5f.png)


  - Composite attribute: Attributes that contain multiple fields or *composed of many other attribute*. Eg: name (first, middle, last name), address (street no., location, city, state), etc.

  Representation: An oval comprising of ovals.
  ![image](https://user-images.githubusercontent.com/44089458/120807475-9d846380-c565-11eb-9add-e3aac4b2f9c5.png)


  - Multivalued attributes: An attribute consisting morce than one value for a given entity. Eg: mobile no. 

  Representation: Double oval 
  ![image](https://user-images.githubusercontent.com/44089458/120807510-a83ef880-c565-11eb-8c0c-f386d3c300c8.png)


  - Derived attributes: An attribute which can be derived from other attributes of the entity type. Eg: Age (derived from DOB)
  
  Representation: Dashed oval 
  ![image](https://user-images.githubusercontent.com/44089458/120807547-b260f700-c565-11eb-9d78-e95a936a21eb.png)


Complete entity type **student** with its attributes:

![image](https://user-images.githubusercontent.com/44089458/120808706-f1437c80-c566-11eb-8b9d-938a982e5cc5.png)
