How to start your journey with chatbot?

1. Open terminal, mount to the file location and enter 'docker-compose -up'

2. Use docker ps to list the containers and find the python container ID.

3. Enter the "docker exec -it [python container_id] bash" to enter the container. Now you are in the Python container.

4. In the send model, enter "pip install redis" to install redis library and the enter "python chatbot.py" to start the chatbot.

5. Now you can follow the instructions provided by chatbot and start your chat with chatbot!

How to monitor your chatbot's working?
1. You can enter "docker exec -it [redis container_id] redis-cli" to enter the redis container.
2. Enter 'MONITOR'. Now you can monitor your chatbot. 

New function: read messages from others:
Clayton send messages to channel 1:
![截屏2023-09-25 20.44.03.png](..%2FDesktop%2F%E6%88%AA%E5%B1%8F2023-09-25%2020.44.03.png)
Then Changzhou see:
![截屏2023-09-25 20.42.05.png](..%2FDesktop%2F%E6%88%AA%E5%B1%8F2023-09-25%2020.42.05.png)
In monitor:![截屏2023-09-25 20.45.21.png](..%2F..%2F..%2Fvar%2Ffolders%2Fb_%2Fygk7t19j3nnbyh1h2mg_7wn80000gn%2FT%2FTemporaryItems%2FNSIRD_screencaptureui_J2xWUk%2F%E6%88%AA%E5%B1%8F2023-09-25%2020.45.21.png)

Same as above, these are the output for at least 3 different user:
Identify and register if not exists:
![截屏2023-09-25 20.54.16.png](..%2F..%2F..%2Fvar%2Ffolders%2Fb_%2Fygk7t19j3nnbyh1h2mg_7wn80000gn%2FT%2FTemporaryItems%2FNSIRD_screencaptureui_n2MW05%2F%E6%88%AA%E5%B1%8F2023-09-25%2020.54.16.png)

Join multiple channels:
![截屏2023-09-25 20.55.52.png](..%2F..%2F..%2Fvar%2Ffolders%2Fb_%2Fygk7t19j3nnbyh1h2mg_7wn80000gn%2FT%2FTemporaryItems%2FNSIRD_screencaptureui_tKmIL1%2F%E6%88%AA%E5%B1%8F2023-09-25%2020.55.52.png)
Help:
![截屏2023-09-25 20.52.21.png](..%2F..%2F..%2Fvar%2Ffolders%2Fb_%2Fygk7t19j3nnbyh1h2mg_7wn80000gn%2FT%2FTemporaryItems%2FNSIRD_screencaptureui_G8AnG3%2F%E6%88%AA%E5%B1%8F2023-09-25%2020.52.21.png)
weather:
![截屏2023-09-25 20.50.59.png](..%2F..%2F..%2Fvar%2Ffolders%2Fb_%2Fygk7t19j3nnbyh1h2mg_7wn80000gn%2FT%2FTemporaryItems%2FNSIRD_screencaptureui_cJ9fhG%2F%E6%88%AA%E5%B1%8F2023-09-25%2020.50.59.png)
Fun fact:
![截屏2023-09-25 20.47.08.png](..%2F..%2F..%2Fvar%2Ffolders%2Fb_%2Fygk7t19j3nnbyh1h2mg_7wn80000gn%2FT%2FTemporaryItems%2FNSIRD_screencaptureui_lM54CR%2F%E6%88%AA%E5%B1%8F2023-09-25%2020.47.08.png)
Who am I:
![截屏2023-09-25 20.51.40.png](..%2F..%2F..%2Fvar%2Ffolders%2Fb_%2Fygk7t19j3nnbyh1h2mg_7wn80000gn%2FT%2FTemporaryItems%2FNSIRD_screencaptureui_mdswZh%2F%E6%88%AA%E5%B1%8F2023-09-25%2020.51.40.png)

Screenshot for monitor:
![截屏2023-09-25 20.58.37.png](..%2F..%2F..%2Fvar%2Ffolders%2Fb_%2Fygk7t19j3nnbyh1h2mg_7wn80000gn%2FT%2FTemporaryItems%2FNSIRD_screencaptureui_js5ZwX%2F%E6%88%AA%E5%B1%8F2023-09-25%2020.58.37.png)
