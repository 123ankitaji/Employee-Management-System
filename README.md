# Employee-Management-System

The Employee Management System is a File structure management system. It provides a user-friendly, interactive Menu Driven Interface (MDI) based on local file systems. All data is stored in files on disk. The application uses file handles to access the files. This project signifies the need for efficient management of employee records in a file. The proposed system enables an administrator to keep track of all the employee details and maintaining records of the employees.

In this system, we have a fixed number of fields, each with a maximum length, that combine to make a data record and variable length record. Fixing the number of fields in a record does not imply that the size of fields in the record is fixed. The records are used as containers to hold a mix of fixed and variable-length fields within a record.
Indexing used in this project is B+ tree implementation. A B+ tree is an N-ary tree with a Variable but often large number of children per node. A B+ tree consists of a root, internal nodes and leaves. The root may be either a leaf or a node with two or more children. A B+ tree can be viewed as a B-tree in which each node contains only keys (not key–value pairs), and to which an additional level is added at the bottom with linked leaves. In this mini project we use 4 keys per node is built to provide the necessary indexing on Employee details.

The primary value of a B+ tree is in storing data for efficient retrieval in a block- oriented storage context in particular, file systems. This is primarily because unlike binary search trees, B+ trees have very high fan out which reduces the number of I/O operations required to find an element in the tree.
