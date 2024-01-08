This API endpoint allows you to parse images by making an HTTP POST request to the specified URL. The request should include a form-data body with the 'images' and 'csv_file' parameters, both of type 'file'.
Request Body
images (file): The image file to be parsed.
csv_file (file): The CSV file containing additional data for parsing.

Response
Upon successful execution, the API returns a status code of 200, along with a JSON response containing cargo space information, cargo details, and unpacked items.
