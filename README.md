Overview for Image aggregator project: 
The main goal of the project is to parse images from the provided site. 
Images can be searched by the presence of a keyword in the title.

The project has a microservice architecture. Here are links to each individual service:
1. Standart Eureka server for registration another services - https://github.com/prowler47/image_aggregator_eureka_service

2. API Gateway service for routing microservices - https://github.com/prowler47/image_aggregator_api-gateway_service

3. Parser service which contains an image parsing engine - https://github.com/prowler47/image_aggregator_parser_service

4. Data service responsible for saving  and storing images in the database - https://github.com/prowler47/image_aggregator_data_service

5. View service for provide user interface - https://github.com/prowler47/image_aggregator_view_service
