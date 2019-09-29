# API Swagger file written with OpenAPI 3.0 syntax organized around the $ref paradigm

Proof of concept folder structure for organizing a Swagger API interface with OpenAPI 3.0

# About this project
This is my first attempt to make a folder structure suitable for organizing 
Swagger files with routes, responses and examples for an API wth OpenAPI 3.0.

There are some current issues that I have encountered with $ref on example file referencing and encoding for query parameters as array in the current OpenAPI implementation of Swagger UI. I have worked around the $ref example problem with inline example and let the encoding statement in place though it doesn't work right now as far as I have tested with the current version of Swagger UI.

I do not claim that this is the way to go for such a type of project but this is the
essence that was perfect for me in terms of intelligibility.

If you pass by let me know your opinion and feel free to use this as starting point for your own perfect folder structure.

Leonardo
