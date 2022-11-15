# downloaderpy
from pytube import YouTube
Link =input("https://www.youtube.com/watch?v=V713DEs4wCs&list=PLIzoD6CTXb3-oHdruO7f3HJ1r9HrcYJ3x&ab_channel=EyadHamza-%CF%80%27sSpace: ")
Video=Yotube("https://www.youtube.com/watch?v=V713DEs4wCs&list=PLIzoD6CTXb3-oHdruO7f3HJ1r9HrcYJ3x&ab_channel=EyadHamza-%CF%80%27sSpace")
stream=Video.streams_get_highest_resoulution()
stream.download()
