# Inception Hiring Case

Create the PRIVATE repository for this case and follow these steps:

## Introduction

This is a case for the Inception hiring process. It is a simple case that will help us understand your skills and how you work. The case is divided into two parts. The first part is a simple coding exercise. The second part is a short written assignment.

### Part 1: Server API Implementation

This coding exercise simple factions API implementation Lua. You need to do these steps:

1. Create a Factions schema on sql *(We're using MySQL)*
2. Create a Factions API with the following endpoints:
    1. Create a faction *(Server event)*
       1. Params: name, type, owner
       2. Returns: cached faction table
    2. Get a faction *(Server event)*
       1. Params: id
       2. Returns: cached faction table
    3. Update a faction
       1. Params: id, key, value
       2. Returns: if update was successful return true, else false
    4. Delete a faction
       1. Params: id
       2. Returns: if delete was successful return true, else false

Requirements:
1. Use async MySQL queries and cache the results in a table.
2. Don't use any external libraries.
3. Don't use *createTeam* or *Team* functions.
4. Use the following table structure:
   1. id
   2. name
   3. type
   4. owner


### Part 2: Client UI Implementation

In this part you need to create a simple UI for the factions API. The UI should have the following features:

1. Faction Detail Window with tabs (Info, Create, etc.)

Requirements:
1. Don't use *GUI* functions.
2. Your design should be responsive.
3. Don't use *getElementData* or *setElementData*.


## Submission

Give access your repository to this email: *enesakilliok17@gmail.com*

Thanks. We will review one by one and get back to you as soon as possible.

[Inception Network](https://github.com/inceptionnet)
