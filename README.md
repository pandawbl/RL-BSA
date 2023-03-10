### Bus Scheduling Problem (BSP) instances

This repository contains 4 real-world BSP instances in Qingdao city, China, which is used in our paper:

> **《A Reinforcement Learning-based Approach for Online Bus Scheduling》**

> There are two main parts：
>
> 1.  **Information of four BSP instances**
> 2. **Timetable and travel time of 4 instances**

1. ##### Information of four BSP instances

| Bus lines                                  | 59    | 60    | 803   | 85    |
| ------------------------------------------ | ----- | ----- | ----- | ----- |
| Earliest departure time                    | 6:00  | 5:50  | 5:20  | 5:30  |
| Latest departure time                      | 20:00 | 22:00 | 22:00 | 23:00 |
| Number of departure times in the timetable | 104   | 120   | 154   | 170   |
| Average travel time of trips (min)         | 41    | 55    | 47    | 35    |
| Maximum working time of short vehicle (h)  | 8     | 8     | 8     | 8     |
| Maximum driving time of short vehicle (h)  | 6.5   | 6.5   | 6.5   | 6.5   |
| Maximum number of trips of long vehicle    | 16    | 12    | 16    | 16    |
| Minimum rest time (min)                    | 3     | 3     | 3     | 3     |

2. ##### Timetable and travel time of 4 instances

Each line has a folder for its data, there are three files in the folder:

| Filename        | Content                                                      |
| --------------- | ------------------------------------------------------------ |
| timetable.txt   | Timetable of control point 1, each row corresponds to a departure time |
| timetable_2.txt | Timetable of control point 2, each row corresponds to a departure time |
| tmessage.txt    | The travel time of vehicles of 24 hours in a day             |

