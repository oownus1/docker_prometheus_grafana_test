# docker_prometheus_grafana_test
- 3000 port grafana test result screenshot
![Screenshot from 2022-08-11 06-00-33](https://user-images.githubusercontent.com/66655878/184110080-e2f713d7-c385-4fa8-8dd2-8c56b736fef5.png)
- 9100 port node exproter test result screenshot 
![Screenshot from 2022-08-11 06-04-35](https://user-images.githubusercontent.com/66655878/184110598-c883ddd0-fbe0-4439-a942-1de63742feef.png)
- 9090 port prometheus test result screenshot 
![Screenshot from 2022-08-11 06-02-55](https://user-images.githubusercontent.com/66655878/184110604-3a40f6d6-3736-4bd4-9519-c4240ec139b6.png)


argon2:$argon2id$v=19$m=10240,t=10,p=8$SqgKSnEPUD5I43NAXfKtdA$yj5wlHpZh4MTIIRbS2Gc04Fobd1zmyqHbSJXsOIZG0w 

- docker + prometheus + grafana 
- 수행한 명렁
```
    1  whoami
    2  cd /bin/bash
    3  cd bin
    4  ls
    5  su - niceadmin
    6  ./vcpkg/bootstrap-vcpkg.bat
    7  ls
    8  cd vcpkg
    9  bootstrap-vcpkg.bat
   10  search freetype
   11  install cuda intel-mkl fftw3 cub kenlm arrayfire[cuda] cudnn nccl openmpi cereal stb gflags glog libsndfile gtest
   12  install cuda intel-mkl fftw3 cub kenlm arrayfire[cuda] cudnn nccl openmpi cereal stb gflags glog libsndfile
   13  niceadmin
   14  su niceadmin
   15  activate pororo_36
   16  conda env list
   17  niceadming
   18  niceadmin
   19  conda niceadmin
   20  login niceadmin
   21  cd ..
   22  cd ..
   23  docker images
   24  docker pull grafana/grafana
   25  docker images
   26  docker ps
   27  docker run -d --name=grafana -p 3000:3000 grafana/grafana
   28  docker ps -a
   29  su niceadmin
   30  su niceadmin
   31  sudo nano /etc/systemd/system/vncserver@1.service
   32  sudo systemctl daemon-reload
   33  sudo systemctl enable vncserver@1.service
   34  sudo systemctl start vncserver@1.service
   35  sudo systemctl status vncserver@1.service
   36  sudo nano /etc/systemd/system/vncserver@1.service
   37  sudo systemctl daemon-reload
   38  sudo systemctl enable vncserver@1.service
   39  sudo systemctl start vncserver@1.service
   40  sudo systemctl status vncserver@1.service
   41  sudo nano /etc/systemd/system/vncserver@1.service
   42  sudo systemctl daemon-reload
   43  sudo systemctl enable vncserver@1.service
   44  sudo systemctl start vncserver@1.service
   45  sudo systemctl status vncserver@1.service
   46  vncserver -list
   47  sudo apt-get install tigervnc-standalone-server tigervnc-xorg-extension
   48  vncpasswd
   49  sudo nano ~/.vnc/xstartup
   50  vncserver -localhost no
   51  vncserver -list
   52  history
   53  ipconfig
   54  ifconfig
   55  nmcli g
   56  nmcli n
   57  nmcli d
   58  ifconfig
   59  apt install net-tools
   60  ifconfig
   61  apt list openshh*
   62  apt install openssh-server
   63  apt list openshh*
   64  apt-get list openshh*
   65  apt list openshh*
   66  systemctl status sshd
   67  ss -nlt
   68  iptables -nL
   69  ufw staus
   70  apt install ufw
   71  ufw status
   72  ufw enable
   73  ufw allow 22/tcp
   74  sudo apt-get install openssh-server
   75  sudo vi /ect/ssh/sshd_config
   76  sudo service ssh start
   77  shdo service ssh stop
   78  sudo service ssh status
   79  sudo ufw enable
   80  sudo ufw allow 22
   81  hostname -l
   82  ssh -p 22 mesf-if@10.115.226.50
   83  host -L
   84  host -l
   85  ssh -p mesf-if@10.115.226.50
   86  ssh -p 22 mesf-if@10.115.226.50
   87  ssh -p 22 oradmin@10.115.226.50
   88  ssh -p 22 otadmin@10.115.226.50
   89  sudo apt-get install ssh
   90  sudo apt-get install -f
   91  sudo vi /ect/ssh/sshd_config
   92  shdo nano /etc/ssh/sshd_config
   93  sudo nano /etc/ssh/sshd_config
   94  sudo service ssh start
   95  sudo sercice ssh stop
   96  sudo service ssh stop
   97  sudo service ssh status
   98  sudo service ssh start
   99  sudo service ssh status
  100  sudo service ssh stop
  101  sudo nano /etc/ssh/sshd_config
  102  sudo service ssh start
  103  sudo service ssh status
  104  ps -ef | grep sshd
  105  ifconfig
  106  sudo netstat -ntlp |grep sshd
  107  ifconfig
  108  ssh -p 22 mesf-if@10.115.226.50
  109  ssh -p 22 otadmin@10.115.226.50
  110  docker ps -a
  111  docker pull bitnami/prometheus:latest
  112  docker ps 0a
  113  docker ps -a
  114  docker images
  115  docker rmi 7b27c1704100
  116  docker ps -a
  117  docker images
  118  docker pull prom/prometheus
  119  docker images
  120  sudo mkdir /etc/prometheus
  121  cd /etc/prometheus
  122  sudo vi prometheus.yml
  123  sudo nano prometheus.yml
  124  docker run -d --name prometheus -p 9090:9090 -v /etc/prometheus/prometheus.yml:/etc/prometheus/prometheus.yml prom/prometheus
  125  docker ps -a
  126  id addr
  127  ip addr
  128  dockar ps -a
  129  docker ps -a
  130  ip addr
  131  docker ps -a
  132  docker run -d --name=prometheus -p 9090:9090 prom/prometheus
  133  docker images
  134  docker ps -a
  135  docker images
  136  docker stop
  137  docker stop 9906431c1c7f
  138  docker rm -f 9906431c1c7f
  139  docker ps -a
  140  docker images
  141  docker rmi c3d2a0b3481a
  142  cd .. 
  143  cd ..
  144  docker pull prom/prometheus
  145  cd /etc/prometheus
  146  sudo nano prometheus.yml
  147  pwd
  148  docker run -p 9090:9090 -v /etc/prometheus/prometheus.yml:/etc/prometheus/prometheus.yml --name prometheus -d prom/prometheus --config.file=/etc/prometheus/prometheus.yml
  149  docker ps -a
  150  docker stop 8feda9b5cdbb
  151  docker ps -a
  152  docker rm -f 8feda9b5cdbb
  153  docker ps 0a
  154  docker ps -a
  155  docker images
  156  docker rmi c3d2a0b3481a
  157  docker ps -a
  158  docker images
  159  sudo nano promethus.yml
  160  sudo nano prometheus.yml
  161  docker run -p 9090:9090 -v /etc/prometheus/prometheus.yml:/etc/prometheus/prometheus.yml --name prometheus -d prom/prometheus --config.file=/etc/prometheus/prometheus.yml
  162  docker pull prom/prometheus:latest
  163  docker run -p 9090:9090 -v /etc/prometheus/prometheus.yml:/etc/prometheus/prometheus.yml --name prometheus -d prom/prometheus --config.file=/etc/prometheus/prometheus.yml
  164  docker ps -a
  165  sudo nano prometheus.yml
  166  docker stop d78b6fef110e
  167  docker ps -a
  168  docker restart d78b6fef110e
  169  docker ps -a
  170  docker stop d78b6fef110e
  171  sudo nano prometheus.yml
  172  docker restart d78b6fef110e
  173  docker ps -a
  174  docker stop d78b6fef110e
  175  docker ps -a
  176  sudo nano prometheus.yml
  177  docker restart d78b6fef110e
  178  docker ps -a
  179  sudo nano prometheus.yml
  180  docker stop d78b6fef110e
  181  docker restart d78b6fef110e
  182  docker ps -a
  183  sudo nano prometheus.yml
  184  docker stop d78b6fef110e
  185  docker restart d78b6fef110e
  186  docker ps -a
  187  sudo nano prometheus.yml
  188  docker run -p 9090:9090 -v /etc/prometheus/prometheus.yml:/etc/prometheus/prometheus.yml --name prometheus -d prom/prometheus
  189  docker ps -a
  190  docker stop d78b6fef110e
  191  docker rm -f d78b6fef110e
  192  docker images
  193  docker run -p 9090:9090 -v /etc/prometheus/prometheus.yml:/etc/prometheus/prometheus.yml --name prometheus -d prom/prometheus
  194  docker ps -a
  195  wget wget https://github.com/prometheus/node_exporter/releases/download/v1.1.2/node_exporter-1.1.2.linux-amd64.tar.gz
  196  tar xvfz node_exporter-1.1.2.linux-amd64.tar.gz
  197  cd node_exporter-1.1.2.linux-amd64/ 
  198  nohup node_exporter >node_exporter.out 2>&1 &
  199  curl localhost:9100/metrics
  200  ls
  201  docker ps -a
  202  cd ..
  203  ls
  204  tar ftz node_exporter-1.1.2.linux-amd64  node_exporter-1.1.2.linux-amd64.tar.gz  prometheus.yml
  205  node_exporter-1.1.2.linux-amd64  node_exporter-1.1.2.linux-amd64.tar.gz  prometheus.yml
  206  tar ftz node_exporter-1.1.2.linux-amd64  node_exporter-1.1.2.linux-amd64.tar.gz  prometheus.yml
  207  ls
  208  tar ftz node_exporter-1.1.2.linux-amd64.tar.gz | xargs rm -rf
  209  ls
  210  rm -rf node_exporter-1.1.2.linux-amd64.tar.gz
  211  ls
  212  docker ps -a
  213  sudo nano prometheus.yml
  214  docker ps -a
  215  pwd
  216  docker run -d --net="host" --pid="host" -v "/:/host:ro,rslave" quay.io/prometheus/node-exporter:latest --path.roofs=/host
  217  docker ps -a
  218  sudo nano prometheus.yml
  219  docker run -p 9090:9090 -v /etc/prometheus/prometheus.yml:/etc/prometheus/prometheus.yml --name prometheus -d prom/prometheus
  220  docker ps -a
  221  docker stop a186d767b369
  222  docker ps -a
  223  docker rm -rf a186d767b369
  224  docker rm -f a186d767b369
  225  docker ps -a
  226  docker run -d --name prometheus -p 9090:9090 -v /etc/prometheus/prometheus.yml:/etc/prometheus/prometheus.yml prom/prometheus
  227  docker ps -a
  228  docker run -p 9090:9090 -v /etc/prometheus/prometheus.yml:/etc/prometheus/prometheus.yml --name prometheus -d prom/prometheus
  229  docker stop dc5d8ce15a6f
  230  docker ps -a
  231  docker rm -f dc5d8ce15a6f
  232  docker run -p 9090:9090 -v /etc/prometheus/prometheus.yml:/etc/prometheus/prometheus.yml --name prometheus -d prom/prometheus
  233  docker ps -a
  234  docker stop 907c40bfcf56
  235  docker rm -f 907c40bfcf56
  236  docekr ps -a
  237  docker run -p 9090:9090 -v /etc/prometheus/prometheus.yml:/etc/prometheus/prometheus.yml --name prometheus -d prom/prometheus
  238  docker ps -a
  239  history
  240  docker ps -a
  241  docker images
  242  docker stop 76167563bfa7
  243  docker rm -f 76167563bfa7
  244  docker rmi c3d2a0b3481a
  245  docker pull prom/prometheus:latest
  246  docker run -p 9090:9090 -v /etc/prometheus/prometheus.yml:/etc/prometheus/prometheus.yml --name prometheus -d prom/prometheus
  247  docker ps -a
  248  docker run -d --name prometheus -p 9090:9090 -v /etc/prometheus/prometheus.yml:/etc/prometheus/prometheus.yml prom/prometheus
  249  docker ps -a
  250  docker rm -f 594b3fec6e7f
  251  docker ps -a
  252  docker run -d --name prometheus -p 9090:9090 -v /etc/prometheus/prometheus.yml:/etc/prometheus/prometheus.yml prom/prometheus
  253  docker ps -a
  254  docker images
  255  docker stop e340f2200e52
  256  docker ps -a
  257  docker images
  258  docker rmi c3d2a0b3481a
  259  docker ps -a
  260  docker stop e340f2200e52
  261  docker images
  262  docker rmi c3d2a0b3481a
  263  docker ps -a
  264  docker stop e340f2200e52
  265  docker ps -a
  266  docker images
  267  docker rmi c3d2a0b3481a
  268  docker stop e340f2200e52
  269  docker rm -f e340f2200e52
  270  docker rmi c3d2a0b3481a
  271  docker ps -a
  272  docker pull prom/prometheus
  273  docker run -d --name prometheus -p 9090:9090 -v /etc/prometheus/prometheus.yml:/etc/prometheus/prometheus.yml prom/prometheus
  274  docker ps -a
  275  sudo nano prometheus.yml
  276  docker images
  277  docker ps -a
  278  docker stop d049125a0d03
  279  docker ps -a
  280  docker stop 41fd3aff02d1
  281  docker ps -a
  282  docker rm -f 41fd3aff02d1
  283  docker images
  284  docker run -p 9090:9090 -v /etc/prometheus/prometheus.yml:/etc/prometheus/prometheus.yml --name prometheus -d prom/prometheus
  285  docker ps -a
  286  docker run -d -p 3000:3000 grafana/grafana
  287  docker ps -a
  288  docker docker stop a365ca9d80c2
  289  docker rm -f a365ca9d80c2
  290  docker ps -a
  291  docker run -d --name=grafana -p 3000:3000 grafana/grafana
  292  docker ps -a
  293  docker stop d049125a0d03
  294  docker ps -a
  295  docker rm -f d049125a0d03
  296  docker ps -a
  297  docker run -d --name=grafana -p 3000:3000 grafana/grafana
  298  docker ps -a
  299  sudo nano prometheus.yml
  300  docker stop ea7a76e5b921
  301  docker rm -f ea7a76e5b921
  302  docker ps -a
  303  docker run -p 9090:9090 -v /etc/prometheus/prometheus.yml:/etc/prometheus/prometheus.yml --name prometheus -d prom/prometheus --config.file=/etc/prometheus/prometheus.yml
  304  docker ps -a
  305  docker stop c3f2061e31db
  306  docker rm -f c3f2061e31db
  307  docker ps -a
  308  docker run -d --name=grafana -p 3000:3000 grafana/grafana
  309  docker ps -a
  310  docker images
  311  docker pull prom/node-exporter
  312  docker images
  313  docker run -d -p 9100:9100 --net="host" prom/node-exporter
  314  docker ps -a
  315  sudo nano prometheus.yml
  316  docker run -d -p 9100:9100 --net="host" prom/node-exporter
  317  docker ps -a
  318  docker stop b0b4b2c8bc51
  319  docker rm -f b0b4b2c8bc51
  320  docker ps -a
  321  docker run -d -p 9100:9100 --network host prom/node-exporter
  322  docker ps -a
  323  docker stop 534c7f2919ac
  324  docker stop 35c8a4bcdee9
  325  docker rm -f 35c8a4bcdee9
  326  docker rm -f 534c7f2919ac
  327  docker ps -a
  328  docker run -d -p 9100:9100 --network host prom/node-exporter
  329  docker ps -a
  330  sudo nano prometheus.yml
  331  docker ps -a
  332  docker stop 3e69ae3a971b
  333  docker rm -f 3e69ae3a971b
  334  docker run -p 9090:9090 -v /etc/prometheus/prometheus.yml:/etc/prometheus/prometheus.yml --name prometheus -d prom/prometheus --config.file=/etc/prometheus/prometheus.yml
  335  dccker ps -a
  336  docker ps -a
  337  docker images
  338  docker ps -a
  339  docker stop 2675b3de704f
  340  docker rm -f 2675b3de704f
  341  docker stop 00df14cf1a6a
  342  docker rm -f 00df14cf1a6a
  343  docker ps -a
  344  docker images
  345  docker rmi 1dbe0e931976
  346  docker ps -a
  347  docker images
  348  docker rmi 1dbe0e931976
  349  docker ps -a
  350  docker stop e61f59d851fc
  351  docker stop f45bcc6d6cef
  352  docker images
  353  docker rmi 1dbe0e931976
  354  docker ps -a
  355  docker restart f45bcc6d6cef
  356  docker ps -a
  357  docker pull prom/node-exporter
  358  sudo docker run -d -p 9100:9100 prom/node-exporter
  359  docker ps -a
  360  sudo nano prometheus.yml
  361  docker restart e61f59d851fc
  362  docker ps -a
  363  id
  364  su - niceadmin
  365  reboot
  366  usermod -u 1001 niceadmin
  367  su - niceadmin
  368  useradd swpark
  369  passwd swpark
  370  pwd
  371  ls
  372  cd ..
  373  ls
  374  cd home
  375  cd ..
  376  mkdir -p /home/swpark
  377  ls -l /home
  378  chown -R swpark:swpark /home/swpark
  379  groupadd testuser
  380  usermod -G testuser swpark
  381  groups swpark
  382  cat /etc/passwd |grep swpark
  383  usermod -s /bin/bash swpark
  384  cat /etc/passwd |grep swpark
  385  su - swpark
  386  docker ps -a
  387  docker stop 53215b21773c
  388  docker stop f45bcc6d6cef
  389  docker stop e61f59d851fc
  390  docker ps -a
  391  docker images
  392  docker ps -a
  393  docker systemctl stop
  394  service docker stop
  395  docker ps -a
  396  reboot
  397  usermod -u 1001 niceadmin
  398  usermod -u 1002 swpark
  399  usermod -u 1002 niceadmin
  400  ps -ef|grep 1083
  401  kill -9 1083
  402  usermod -u 1002 niceadmin
  403  kill -9 1089
  404  usermod -u 1002 niceadmin
  405  kill -9 1145
  406  usermod -u 1002 niceadmin
  407  kill -9 1249
  408  usermod -u 1002 niceadmin
  409  kill -9 2911
  410  nano /etc/default/grub
  411  cat /etc/default/grub
  412  sudo update-grub
  413  reboot
  414  docker ps -a
  415  history
  416  sudo apt-get install xserver-xorg-input-all
  417  reboot
  418  docker ps -a
  419  history
  420  docker ps -a
  421  docker service start
  422  docker ps -a
  423  docker restart f45bcc6d6cef
  424  docker restart 53215b21773c
  425  docker restart e61f59d851fc
  426  docker ps -a
  427  sudo apt-get install xserver-xorg-input-all
  428  docker ps -a
  429  reboot
  430  history
```
#
- prometheus.yml 
```
global:
  scrape_interval: 15s
  evaluation_interval: 15s
# By default, scrape targets every 15 seconds.
 # Attach these labels to any time series or alerts when communicating with 
 # external systems (federation, remote storage, Alertmanager).
# external_labels:
 #  monitor: 'node'
# A scrape configuration containing exactly one endpoint to scrape:
# Here it's Prometheus itself. 
scrape_configs:
  # The job name is added as a label `job=<job_name>` to any timeseries scraped from this config.

    # Override the global default and scrape targets from this job every 5 seconds.
    #scrape_interval: 5s 
  - job_name: 'prometheus'
    static_configs:
      - targets: ['172.28.4.244:9090']
  - job_name: 'node-exporter'
    static_configs:
      - targets: ['172.28.4.244:9100']
  - job_name: 'win10'
    static_configs:
      - targets: ['172.28.4.103:9182']

```

