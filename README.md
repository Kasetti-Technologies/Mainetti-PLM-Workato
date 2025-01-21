# Mainetti-PLM-Workato
Repository related to PLM Workato integration with Mainettis 40 ERP Systems

The Centric 8 REST API is based on the HTTP open standard. One communicates by making a standard HTTP request and getting the result back in an HTTP response. The API allows CRUD operations to be performed by invoking the API using HTTP POST, GET, PUT and DELETE request methods. The API will restrict the logged-in API user to the CRUD operations authorized by their C8 role. 

Ref: C8_7 7_REST API Developer Guide_ document https://drive.google.com/file/d/1jcA2GAOxy_sbSDYOcw8_RK0paGXUEf2k/view?usp=drive_link


# Centric Shadow Table
C8 introduces enhancements to its REST API through the concept of "Custom Shadow Tables." These tables leverage C8's custom view functionality to significantly improve data retrieval efficiency.

The custom shadow table view enhancements enable the retrieval of data from a C8 custom view through the REST API using GET requests with incremental updates. This functionality allows for flexible data assembly via relationships, spanning multiple object domains. By leveraging C8 custom views, you can bypass traditional endpoint boundaries, simplifying the management of complex data structures. Relationships are derived directly from the custom view definition, and results are pre-assembled, reducing programming effort.


Instead of relying on traditional REST endpoint formats, you can retrieve data using the C8 custom view format. This approach consolidates related data from across object domain boundaries into a single unit, minimizing the number of GET requests required. Custom views can incorporate one or more matrices, further enhancing flexibility.

Ref Centric Shadow Table Sample JSON: Centric\Centric Shadow Table.json
Link: https://github.com/Kasetti-Technologies/Mainetti-PLM-Workato/blob/main/Centric%20Shadow%20Table.json

Doc Ref:
Supplier Shadow Table REST API: https://docs.google.com/document/d/1Sv0ZFh5yuS7TKHU59Grv8zDemJ2fOke6/edit
Supplier Shadow Table Rest API 2: https://docs.google.com/document/d/1rltwrcGO-d0TC3tWT-0tCG3vA6q5U1pc/edit?usp=drive_link&ouid=114462600381337779852&rtpof=true&sd=true
Material Shadow Table REST API: https://docs.google.com/document/d/1qS8K4WS35DxHzEr4LLoxLZNA-cetwOPO/edit?usp=drive_link&ouid=114462600381337779852&rtpof=true&sd=true