# doc-gen - the below content was created by this tool

This Flask application allows users to upload code files and receive professionally explained documentation generated by the GPT-3.5 model from OpenAI.

The code reads the content of the uploaded file, prepares a payload for the OpenAI chat API with the code content, and includes a system message to guide the response.
It sends a POST request to the OpenAI chat completion API endpoint using the provided API key and retrieves the completed documentation.
If the response is successful, the documentation is formatted in HTML <pre> tags to enhance readability.
The application handles GET requests by rendering an upload form where users can select a file to upload.
It runs the Flask application in debug mode when executed directly.
Remember to replace the API_KEY variable with your actual OpenAI API key to use this application effectively.