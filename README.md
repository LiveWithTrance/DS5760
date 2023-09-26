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
<img width="257" alt="截屏2023-09-25 20 44 03" src="https://github.com/LiveWithTrance/DS5760/assets/111295481/d06fb2be-86b0-4f30-8481-768ef7afc823">

Then Changzhou see:
<img width="474" alt="截屏2023-09-25 20 42 05" src="https://github.com/LiveWithTrance/DS5760/assets/111295481/79cfef44-7a23-471c-8eff-36129b251d7a">
In monitor:
<img width="987" alt="截屏2023-09-25 21 15 57" src="https://github.com/LiveWithTrance/DS5760/assets/111295481/0bb2536f-8b1a-4d15-ab05-b596b8a76e5a">

Same as above, these are the output for at least 3 different user:
Identify and register if not exists:
<img width="734" alt="截屏2023-09-25 21 16 22" src="https://github.com/LiveWithTrance/DS5760/assets/111295481/08410bf3-9011-41cc-8155-2e32fb07ba22">

Join multiple channels:
<img width="693" alt="截屏2023-09-25 21 16 47" src="https://github.com/LiveWithTrance/DS5760/assets/111295481/ac770be7-36d6-4820-a0d4-96b0bb6f89fc">

Help:
<img width="866" alt="截屏2023-09-25 21 17 04" src="https://github.com/LiveWithTrance/DS5760/assets/111295481/b33f5918-afca-47ce-a257-7a1cdb3344fd">

weather:
<img width="557" alt="截屏2023-09-25 21 17 33" src="https://github.com/LiveWithTrance/DS5760/assets/111295481/8c51ce0d-d36e-4226-b577-e51ce9177ee8">

Fun fact:
<img width="1035" alt="截屏2023-09-25 21 17 54" src="https://github.com/LiveWithTrance/DS5760/assets/111295481/5622b4b2-e0f5-4c50-bde1-3f903722939e">

Who am I:
<img width="455" alt="截屏2023-09-25 21 18 02" src="https://github.com/LiveWithTrance/DS5760/assets/111295481/59ed2e8f-ea98-44dd-9c52-59971d1d6e2b">

Screenshot for monitor:
<img width="1020" alt="截屏2023-09-25 21 18 23" src="https://github.com/LiveWithTrance/DS5760/assets/111295481/1df120f8-8351-401f-890e-400a38cd2f8d">
