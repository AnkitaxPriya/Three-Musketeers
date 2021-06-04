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
- **Relationship Set**
  - Weak Entity Relation 
- **Attributes**
  - Key attribute: The attribute which uniquely identifies each entity in the entity set. Eg: roll no. 

  Representation: An oval with underlying lines. 

  - Composite attribute: Attributes that contain multiple fields or *composed of many other attribute*. Eg: name (first, middle, last name), address (street no., location, city, state), etc.

  Representation: An oval comprising of ovals.

  - Multivalued attributes: An attribute consisting morce than one value for a given entity. Eg: mobile no. 

  Representation: Double oval 

  - Derived attributes: An attribute which can be derived from other attributes of the entity type. Eg: Age (derived from DOB)
  
  Representation: Dashed oval 
