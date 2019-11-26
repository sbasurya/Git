	  2  cat /etc/*lease*
	
    3  curl -fsSL https://get.docker.com -o get-docker.sh
	
    4  ls
	
    5  docker --version
	
    6  sh get-docker.sh
	
    7  systemctl restart docker
	
    8  docker --version
	
    9  exit
	
   10  docker info
   
   11  cd /var/lib/docker
   
   12  ls
   
   13  cd image/

   14  ls

   15  cd devicemapper/

   16  ls

   17  cd imagedb/

   18  ls

   19  cd content/

   20  ls

   21  cd sha256/

   22  ls

   23  cd ..

   24  ls

   25  cdm..

   26  cd ..

   27  ls

   28  cd ..

   29  cd repositories.json
   
   30  cat repositories.json
   
   31  ls
   
   32  cd ,,
   
   33  cd ..
   
   34  ls
   
   35  docker pull centos
   
   36  ls
   
   37  cd devicemapper/
   
   38  ls
   
   39  cat repositories.json
   
   40  ls
   
   41  cd imagedb/
   
   42  ks

   43  ls

   44  cd metadata/

   45  ls

   46  cd sha256/

   47  ls

   48  cd ..

   49  ls

   50  cd content/

   51  ls

   52  cd sha256/

   53  ls

   54  docker pull ubuntu

   55  la

   56  ls

   57  cd ..

   58  ls

   59  cd ..

   60  ls

   61  cd image/

   62  ls

   63  cd devicemapper/

   64  ls

   65  cd ,,

   66  cd ..

   67  ls

   68  cd plugins/

   69  l

   70  ls

   71  cd ,,

   72  cd ..
   73  cd volumes/

   74  ls

   75  cat metadata.db

   76  cd ..

   77  ls

   78  cd network/

   79  ls

   80  cd files/

   81  ls

   82  cd

   83  cd /var/lib/docker

   84  ls

   85  cd

   86  cd /var/log/

   87  ls

   88  docker info

   89  cd /var/lib/docker

   90  ls

   91  cd containers/

   92  ls

   93  cd f4d8f102f280877ab81a65ebc7397dc9b3a44837743f4697ccc6f4e013fcd394/

   94  ls

   95  cd f4d8f102f280877ab81a65ebc7397dc9b3a44837743f4697ccc6f4e013fcd394-json.log

   96  cat f4d8f102f280877ab81a65ebc7397dc9b3a44837743f4697ccc6f4e013fcd394-json.log

   97  cd

   98  cd /etc/docker/

   99  ls

  100  cat key.json

  101  touch daemon.json

  102  cat daemon.json

  103  cd ..

  104  ls

  105  cd

  106  ls

  107  docker inages

  108  docker images

  109  docker pull sforcloud/demo-tomcat

  110  docker images

  111  docker pull centosq

  112  docker pull centos

  113  docker run --rm -itd centos bash

  114  docker exec -it 0b6a116a12 bash

  115  docker ps

  116  docekr pull centos:7

  117  docker pull centos:7

  118  docker images

  119  docker images --help

  120  docker images docker ps

  121  docker ps

  122  docker run -itd centos ls

  123  docker ps

  124  docker ps -a

  125  docker run -itd centos top

  126  docker ps -a

  127  docker run -itd --name shiva centos

  128  docker ps -a

  129  docker run -itd --name devops centos

  130  docker ps -a

  131  docker run -itd --name devops centos

  132  docker

  133  docker rename


  134  docker ps

  135  docker rename b118f242f396 DEVOPS

  136  docker ps

  137  docker ps --help

  138  docker ps -q

  139  docker ps -n

  140  docker ps -n 1

  141  docker ps -n 2

  142  docker ps -n 3

  143  docker ps -l

  144  docker ps -s

  145  dockr ps -

  146  docker ps -1

  147  docker ps -q

  148  docker rm

  149  docker rm $(docker ps -q)

  150  docker rm -f $(docker ps -q)

  151  docker ps

  152  docker ps -a

  153  docker rm -f $(docker ps -aq)

  154  docker prune

  155  docker container prune

  156  docker ps

  157  docker ps -a

  158  docker pull nginx

  159  docker images

  160  docker run -itd nginx

  161  docker pa

  162  docker ps

  163  docker container inspect 4a30f08c9ada

  164  ping 172.17.0.2

  165  lynx 172.17.0.2

  166  yum install lynx

  167  lynx 172.17.0.2

  168  docker run -itd -p 90:80 nginx

  169  docker ps

  170  netstat -lntup

  171  telnet

  172  telnet localhost 90

  173  telnet localhost 9090

  174  telnet localhost 90

  175  docker ps

  176  docker run -itd -p 90:90 nginx

  177  docker run -itd -p 100:90 nginx

  178  docker ps

  179  docker run -itd centos ls

  180  docker run -itd centos top

  181  docker ps

  182  docker logs

  183  docker logs e91c0714645b

  184  docekr ps -a

  185  docker ps -a

  186  docker logs cc08822413c9

  187  docker logs a17f6e1b74ea

  188  docker logs 4a30f08c9ada

  189  watch docker logs 4a30f08c9ada

  190  watch docker logs ff7f5ab5a83c

  191  docker logs ff7f5ab5a83c

  192  watch docker logs ff7f5ab5a83c

  193  docker ps

  194  docekr

  195  docker

  196  docker stats

  197  docker

  198  docker ps

  199  docker exec -it e91c0714645b ls

  200  docker exec -it e91c0714645b cat /etc/redhat-release

  201  docker exec -it e91c0714645b cat /etc/*releae*

  202  docker exec -it e91c0714645b cat /etc/*release*

  203  docker attach -it e91c0714645b

  204  docker attach 91c0714645b

  205  docker attach

  206  docker attach --help

  207  docker  ps

  208  docker attach e91c0714645b

  209  docker  ps

  210  docker  ps -a

  211  docker attach e91c0714645b

  212  docker attach ff7f5ab5a83c

  213  docker images

  214  docker image inspect 231d40e811cd

  215  docker network ls

  216  docker network inspect 23e7d333b634

  217  ipp addr sow

  218  ipp addr show

  219  ip addr sho

  220  docker volumes

  221  docker volume

  222  docker volume ls

  223  docker info

  224  systemctl status docker

  225  systemctl start docker

  226  systemctl status docker.service

  227  history

  228  systemctl status docker

  229  systemctl restart docker

  230  journalctl -xe

  231  ps -ef | docker

  232  ps -ef | grep  docker

  233  cat /etc/passwd

  234  cd /etc/docker/

  235  ls

  236  cat daemon.json

  237  rm -rf daemon.json

  238  ls

  239  cd ..

  240  cd

  241  exit

  242  systemctl start docker

  243  systemctl status docker

  244  systemctl enable docker

  245  history

  246  docker images

  247  docker ps

  248  docker ps -a

  249  docker container prune

  250  docker ps -a

  251  docker run -itd --name image1 centos

  252  docker ps

  253  docker exec -it fbe4c1fcc741 bash

  254  docker run -itd --name image2 centos

  255  docker ps

  256  docker run -itd image2 bash

  257  docker exec -it image2 bash

  258  docker exec -it image1 bash

  259  docker images


  260  docker ps

  261  docker exec -it image1 bash

  262  docker ps

  263  docker commit

  264  docker commit fbe4c1fcc741 centos-vim

  265  docker images

  266  docker run -itd --name image-vim centos-vim

  267  docker ps

  268  docker exec -it image-vim bash

  269  docker images

  270  ls

  271  touch Dockerfile

  272  ls

  273  vim Dockerfile

  274  docker build -t build-centos .

  275  vim Dockerfile

  276  docker build -t build-centos .

  277  docker images

  278  docker run -it build-centos telnet localhost 80

  279  docker run -it build-centos vim test

  280  docker ps

  281  docker ps -a

  282  vim Dockerfile

  283  docker build -t ubuntu-build .

  284  docker images

  285  docker run -itd ubuntu-build bash

  286  docker exec -it a6678bf198 bash

  287  touch hello.sh

  288  touch sample.txt

  289  vim sample.txt

  290  ls

  291  vim Dockerfile

  292  docker build -t ubuntu-copy .

  293  docker run -it ubuntu-copy cat /tmp/sample.txt

  294  docker ps -a

  295  vim Dockerfile

  296  docker build -t ubuntu-add .

  297  vim Dockerfile

  298  docker build -t ubuntu-add1 .

  299  docker images

  300  docker run -it ubuntu-add bash

  301  docker run -it ubuntu-add1 bash

  302  vim Dockerfile
  303  docker build -t ubuntu-s3 .

  304  docker run -it ubuntu-s3 bash

  305  vim Dockerfile

  306  docker build -t ubuntu-s31 .

  307  vim Dockerfile

  308  docker build -t ubunti-top .

  309  vim Dockerfile

  310  docker build -t ubunti-top .

  311  docker images

  312  docker run -it ubunti-top

  313  docker ps

  314  docker ps -q

  315  docker ps -aq

  316  docker rm -f $(docker ps -aq)

  317  docekr ps -a

  318  docker ps -a

  319  docker images

  320  docker run -it ubunti-top

  321  vim Dockerfile

  322  docker build -t ubunti-ls .

  323  docker images

  324  docker run -it ubunti-ls

  325  vim Dockerfile

  326  docker build -t ubunti-lstop .

  327  docker images

  328  docker run -it ubunti-lstop

  329  docker run -it ubunti-lstop date

  330  docker run -it ubunti-lstop pwd

  331  docker run -it ubunti-lstop w

  332  vim Dockerfile

  333  docker build -t ubunti-entry .

  334  docker images

  335  docker run -it ubunti-entry

  336  docker run -it ubunti-entry ls

  337  docker run -it ubunti-entry top

  338  date

  339  date --help

  340  date %a

  341  date %A

  342  date --help

  343  date --date='TZ="America/Los_Angeles" 09:00 next Fri'

  344  vim Dockerfile

  345  docker build -t ubuntu-entry-ls .

  346  docker run -it ubuntu-entry-ls

  347  docker run -it ubuntu-entry-ls -a

  348  docker run -it ubuntu-entry-ls -ll

  349  docker run -it ubuntu-entry-ls ll

  350  docker run -it ubuntu-entry-ls -al

  351  vim Dockerfile

  352  docker run -it ubuntu-entry-ls -al

  353  docker build -t ubuntu-entry-ls .

  354  docker run -it ubuntu-entry-ls -al

  355  docker build -t ubuntu-entry-ls1 .

  356  docker run -it ubuntu-entry-ls

  357  docker run -it ubuntu-entry-ls

  358  docker run -it ubuntu-entry-ls al

  359  docker run -it ubuntu-entry-ls ls -al

  360  docker images

  361  docker run -it ubuntu-entry-ls1

  362  docker run -it ubuntu-entry-ls1 al

  363  docker run -it ubuntu-entry-ls1 -al

  364  vim Dockerfile

  365  docker build -t ubuntu-entry-1 .

  366  docker images

  367  docker run -it ubuntu-entry-1

  368  docker run -it ubuntu-entry-1 ls

  369  docker run -it ubuntu-entry-1 ls -al

  370  ls -al

  371  docker run -it ubuntu-entry-1 -al



