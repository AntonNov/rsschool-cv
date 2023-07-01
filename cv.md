1. Novikov Anton
![My_photo](https://avatars.githubusercontent.com/u/56130014?s=400&u=389bf44a9a9ad2fed046025d6cca239b761e6d85&v=4)
2. Сontact with me:
- [Telegram](https://t.me/moooooooorka)
- [email](anton.nov123@gmail.com)
- discord nickname at rsschool server: ontosheg (@AntonNov)
3. Solution of [Can you get the loop ?](https://www.codewars.com/kata/can-you-get-the-loop) kata from [Codewars](https://www.codewars.com/) as code example: 
```python
def loop_size(node):
    turtle = hare = node
    hare = hare.next.next
    turtle = turtle.next
    while hare != turtle:
        hare = hare.next.next
        turtle = turtle.next
    hare = hare.next.next  
    turtle = turtle.next
    cnt = 1
    while hare != turtle:
        turtle = turtle.next
        hare = hare.next.next
        cnt += 1
    return cnt 
```
8. English B1
