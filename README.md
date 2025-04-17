# Delhivery-Feature-Enginnering

❓ What is Delhivery Business Case Study?

- Delhivery, India's leading and rapidly growing integrated player, has set its sights on creating the commerce operating system. They achieve this by utilizing world-class infrastructure, ensuring the highest quality in logistics operations, and harnessing cutting-edge engineering and technology capabilities.
🎯 Objective:

1) The company wants to understand and process the data coming out of data engineering pipelines:

2) Clean, sanitize and manipulate data to get useful features out of raw fields

3) Make sense out of the raw data and help the data science team to build forecasting models on it

📚 About Data:

📃 Features of the dataset:

1) data - tells whether the data is testing or training data

2) trip_creation_time – Timestamp of trip creation

3) route_schedule_uuid – Unique Id for a particular route schedule
4) route_type – Transportation type
FTL – Full Truck Load: FTL shipments get to the destination sooner, as the truck is making no other pickups or drop-offs along the way

Carting: Handling system consisting of small vehicles (carts)

6) trip_uuid - Unique ID given to a particular trip (A trip may include different source and destination centers)

7) source_center - Source ID of trip origin

8) source_name - Source Name of trip origin

9) destination_cente – Destination ID

10) destination_name – Destination Name

11) od_start_time – Trip start time

12) od_end_time – Trip end time

13) start_scan_to_end_scan – Time taken to deliver from source to destination

14) is_cutoff – Unknown field

15) cutoff_factor – Unknown field

16) cutoff_timestamp – Unknown field

17) actual_distance_to_destination – Distance in Kms between source and destination warehouse

18) actual_time – Actual time taken to complete the delivery (Cumulative)

19) osrm_time – An open-source routing engine time calculator which computes the shortest path between points in a given map (Includes usual traffic, distance through major and minor roads) and gives the time (Cumulative)

20) osrm_distance – An open-source routing engine which computes the shortest path between points in a given map (Includes usual traffic, distance through major and minor roads) (Cumulative)

21) factor – Unknown field

22) segment_actual_time – This is a segment time. Time taken by the subset of the package delivery

23) segment_osrm_time – This is the OSRM segment time. Time taken by the subset of the package delivery

24) segment_osrm_distance – This is the OSRM distance. Distance covered by subset of the package delivery

25) segment_factor – Unknown field
