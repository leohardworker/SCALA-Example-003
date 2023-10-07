This code models the management of plastic injection machines, products, and raw materials, allowing for production scheduling and stock management based on processing times and available raw materials.
In this example, the InjectionMachine class represents injection molding machines.
The ERPSystem class manages injection molding machines, products, and raw material inventory.
Instances are created through the Main object to execute the program. 
This program focuses on simulating business processes related to plastic injection molding machines, including managing production schedules, stock levels, and raw material inventory.
InjectionMachine Class:
The InjectionMachine class represents injection molding machines. It contains the name (name) and processing time (processingTime) for each injection machine. The processing time indicates how long the machine needs to operate to produce products.

Product Class:
The Product class represents the products manufactured in the business. It includes the product name (name), stock quantity (stock), price (price), manufacturing time (manufacturingTime), and the raw material quantities used (rawMaterials).

ERPSystem Class:
The ERPSystem class manages all aspects of the business processes. It includes injection machines (InjectionMachine), products (Product), and raw material inventory. This class contains methods to add machines, manage products, update stocks, simulate product production, and list existing products.

Add Machine Method:
The addMachine method is used to add a new injection molding machine. It takes the machine name and processing time as parameters and adds the machine to the system.

Add Product Method:
The addProduct method is used to add a new product. It takes the product name, stock quantity, price, manufacturing time, and raw material details, then adds the product to the system.

Update Stock Method:
The updateStock method updates the stock quantity of a specific product. It takes the product name and the new stock quantity as parameters and updates the stocks.

Produce Product Method:
The produceProduct method produces a specific product using a specified machine. It takes the product name and machine name as parameters and simulates the production process, performing raw material checks during the simulation.

List Products Method:
The listProducts method lists the existing products and their details. This method provides a detailed overview of the products available in the inventory.

Main Object:
The Main object serves as the entry point of the program. It instantiates the ERPSystem class and calls methods that simulate business processes.

Simulation of Injection Molding Process:
This program simulates the working hours of plastic injection molding machines and the usage of raw materials. Product manufacturing processes, machine operating times, and raw material consumption are modeled within the program.

Management of Production Schedules:
The program manages the scheduling of products based on their manufacturing times and the operating times of available machines. It plans the production of products according to their production schedules.

Stock Control:
Stock control is maintained through the updateStock method. It updates product stocks and monitors stock levels.

Handling Raw Materials:
The quantities of raw materials required for product manufacturing are represented through the rawMaterials property in the Product class. The program verifies raw material quantities and ensures there are enough materials available for production.

Comprehensive Business Process Simulation:
This program comprehensively models complex business processes, simulating product production, stock control, and raw material management. This enables efficient planning and management of operational processes within the business.
