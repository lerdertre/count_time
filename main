import time

def count_time():
  this_time=time.time()
  d=int((zk-this_time)//86400)
  h=int(((zk-this_time)-(d*86400))//3600)
  m=int(((zk-this_time)-(d*86400)-(h*3600))//60)
  s=int(((zk-this_time)-(d*86400)-(h*3600)-(m*60))//1)
  print('距离中考仅剩{}天{}小时{}分{}秒'.format(d,h,m,s),end='\r')

zk=1624496400

while True:
  count_time()
  time.sleep(1)
