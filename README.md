# BackendExam


### The code demonstrates Producer-Consumer Pattern - a classic synchronization problem Using .NET 5

![image](https://user-images.githubusercontent.com/77055368/155300805-da44e7f5-74b2-47fa-a7e2-93b2d25dd64d.png)

## Producer
The `m_ProducerTask` Task will generate data in random interval between 0.1 and 1 second.

Generated data will be enqueued to `DataQueue` object.


## Consumer
The `m_ConsumerTask` should fetch the data asynconiusly and processes it using `DecodeData()` method.

`DecodeData()` method will run between 0.01 and 0.3 seconds to simulate process.


Implement the following:
 - Processing should keep the order of equeued messages - FIFO
 - Watch for excessive CPU usage
 - Fill free to change the collection type and other components if needed



# Don't use pull request in the repository
# The solution should be sent as reply email to the interviewer

