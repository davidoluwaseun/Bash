Task: Implement RESTCONF API Calls in Bash
Task Name: Implement RESTCONF API Calls in Bash

Task Preparation
To perform this task, you need to ensure the following:

Have access to a network device that supports RESTCONF API.
Install cURL on your Linux machine (if not already installed) using the package manager for your distribution.

Task Implementation
To implement the RESTCONF API calls in Bash, I followed these steps:

Create a bash script file.
Define the necessary variables, such as the IP address of the host, RESTCONF credentials, data format, and interface details.
Construct the REST API URLs for PUT and GET requests.
Set the headers and authentication for the requests.
Prepare the payload data for the PUT request.
Make the PUT request using cURL and capture the status code.
Make the GET request using cURL and capture the status code and interface information.
Output the results.

Task Troubleshooting
Following troubleshooting steps:

I checked the connectivity to the host and ensure it is reachable from your Linux machine.
I verify the correctness of the RESTCONF credentials and API URLs.
Ensure cURL is installed and accessible from the command line.
Validate the payload data format and structure for the PUT request.
Inspect any error messages or status codes returned by the API calls for debugging.

Task Verification
Verified the quality of the result, follow these steps:

Run the bash script.
Check the generated check_restconf_api.txt file for the output.
Ensure that the output includes the current date, start and end markers, status codes, and interface information.
Compare the obtained results with the expected behavior of the RESTCONF API.


# Bash
