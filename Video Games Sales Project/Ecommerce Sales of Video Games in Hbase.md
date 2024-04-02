# Ecommerce Sales of Video Games in Hbase
There is an existing MySQL Table already with the video games data. But there are no Primary or Unique value columns there. So we will get an error regarding row-key. To avoid that we are adding a column named id which will have unique values.
![image](https://github.com/abirbhattacharya82/IBM-Big-Data-Training-Projects/assets/70687014/6dd64f84-b6ff-4f37-842b-4b5f90c15b9c)

### Creating the Table
```
create 'video_games_table','cf1'
```
### Importing Data from MySQL to Hbase
![image](https://github.com/abirbhattacharya82/IBM-Big-Data-Training-Projects/assets/70687014/ed6bfdd0-ac43-4e5c-aad7-21c6da995597)
