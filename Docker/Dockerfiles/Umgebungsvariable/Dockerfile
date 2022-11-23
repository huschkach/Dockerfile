FROM ubuntu:18.04
WORKDir /home
ENV Name='Tony Stark' \
    Password='zu Musk'
RUN apt update; \
    apt install -y python3; \
    echo "print('Guten Morgen ${Name}, dein Passwort ist ${Password}!')" >> /home/hello.py;
CMD ["python3", "-c","print('Guten Morgen $Name, dein Passwort ist $Password!')"]