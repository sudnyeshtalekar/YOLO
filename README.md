## Image Proceesing Project (CSE4019)
### Implementation of CNN for Real Time Object detection & comparing results of two different algorithms.

## Before You Start ⚠️

To run this project Download the weights from [https://pjreddie.com/media/files/yolov3.weights](https://pjreddie.com/media/files/yolov3.weights)


| Parameter | YOLO  | Primitive R-CNN | Google Vision API | IBM Watson Bluemix API |
| ---------- | ------------- | ------------- | ------------- | -------------------- |
| **Realtime Performance** | Less performance hungry then other algorithms | CPU usage max out while running it. | No performance outage but network speed comes to matter | Same as Google Vision API |
| **FPS(Frames per second)** | Usually 30-50 FPS observed with decent hardware. But can increase with good GPU’s | Hardly 2-5 FPS observed due to deep and more complex neural network | Depends on network availability. Generally less than 25 FPS | Depends on network availability |
| **Memory Complexity** | Use more as compared to API’s but less than R-CNN | Heavy memory logging issue found which even slows down the host OS. | No memory overhead since API calling only depends on network | No memory overhead since API calling only depends on networky |
| **Performance** | Performance very good and can be used for commercially application like autonomous driving (Tesla cars) | Due to poor performance it is not viable to use for real time application. But it's good start for beginners since easy to learn concepts. | Again it depends on network performance like ping, data speed. But after successful deployment of 5G this will be the Industry standards. | Again it depends on network performance like ping, data speed. But after successful deployment of 5G this will be the Industry standards. |
| **Time Complexity** | Takes less time to compute. | Takes more time to commute since more performance hungry | Depends on network as well as server capacity to handle the request. | Depends on network as well as server capacity to handle the request. |
| **Reliability** | Most reliable of all since it is independent of network usage | Reliable but due to poor performance, not practical for use. | Not reliable for real time since the network can fluctuate anytime. If a stable network is provided then there can be the possibility of the server not able to handle a lot of request peak hours. | Not reliable for real time since the network can fluctuate anytime. If a stable network is provided then there can be the possibility of the server not able to handle a lot of request peak hours. |
| **Efficiency** | Efficient if good hardware is provided. | Not efficient | Efficient provided good network | Efficient provided good network |
| **Cost** | Cost effective given that use case satisfies the cost. | Costly since very expensive hardware is required for computation | Cheap since Google Vision API (GCP credit) $300 free per month | Cheap since Watson API is bundled with other services like NLP which can be integrated. |
