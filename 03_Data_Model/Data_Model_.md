Data Model & Architecture Overview

The data model is built using a Star Schema centered around the Dim_Country table.
Relationships are established with a 1-to-Many cardinality between Dim_Country and the facts.
All DAX measures are centralized in a dedicated _All Measures table for optimal management.
