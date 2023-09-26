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

<img width="257" alt="截屏2023-09-25 20 44 03" src="https://github.com/LiveWithTrance/DS5760/assets/111295481/d62fde20-5bd3-448c-a3cf-2d9faef7e514">


Then Changzhou see:

<img width="474" alt="截屏2023-09-25 20 42 05" src="https://github.com/LiveWithTrance/DS5760/assets/111295481/d47e2b27-d708-4d52-9105-b18667b5a747">



In monitor:

<img width="992" alt="截屏2023-09-25 21 23 52" src="https://github.com/LiveWithTrance/DS5760/assets/111295481/f89cd668-9788-4e9f-b434-52d6d4122ddb">

Same as above, these are the output for at least 3 different user:

Identify and register if not exists:

<img width="734" alt="截屏2023-09-25 21 16 22" src="https://github.com/LiveWithTrance/DS5760/assets/111295481/38208caa-e560-498e-bdb0-5583a85b934d">


Join multiple channels:


<img width="676" alt="截屏2023-09-25 21 24 42" src="https://github.com/LiveWithTrance/DS5760/assets/111295481/6d6e54a0-751a-48c8-8997-ff977e2417b8">


Help:


<img width="866" alt="截屏2023-09-25 21 17 04" src="https://github.com/LiveWithTrance/DS5760/assets/111295481/355f7738-9192-4e19-ac3d-8ffd180a60a6">


weather:


<img width="557" alt="截屏2023-09-25 21 17 33" src="https://github.com/LiveWithTrance/DS5760/assets/111295481/5bdef1ec-26dd-4abe-9614-7fccc75d6e15">

Fun fact:

<img width="883" alt="截屏2023-09-25 21 25 20" src="https://github.com/LiveWithTrance/DS5760/assets/111295481/03ddd79c-4d82-47b3-ba3b-0c92678aef7a">

Who am I:

<img width="450" alt="截屏2023-09-25 21 25 36" src="https://github.com/LiveWithTrance/DS5760/assets/111295481/b7a753c2-39ad-4811-910d-7e9c8d4fd109">


Screenshot for monitor:


<img width="1358" alt="截屏2023-09-25 21 25 50" src="https://github.com/LiveWithTrance/DS5760/assets/111295481/24a4f6bc-6e7f-4b87-a067-0d192f688940">
