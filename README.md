# K8s-deploy


Code Upto CMD History 

  1  sudo apt-get i
    2  sudo apt-getupdate
    3  sudo apt-get update
    4  git
    5  sudo apt install git
    6  ssh
    7  wget https://github.com/kubernetes/kops/releases/download/1.12.3/kops-linux-amd64
    8  git pulll https://github.com/niteshldd/K8s-deploy.git
    9  git pull https://github.com/niteshldd/K8s-deploy.git
   10  git pull https://github.com/niteshldd/K8s-deploy
   11  git clone https://github.com/niteshldd/K8s-deploy.git
   12  ls
   13  chmod +x kops-linux-amd64
   14  mv kops-linux-amd64 /usr/local/bin/
   15  sudo mv kops-linux-amd64 /usr/local/bin/
   16  sudo apt-get install python-pip
   17  pip
   18  sudo pip install awscli
   19  aws configure
   20  ls -ahl ~/.aws/
   21  wget https://storage.googleapis.com/kubernetes-release/release/v1.15.0/bin/linux/amd64/kubectl
   22  ls
   23  sudo mv kubectl /usr/local/bin/
   24  sudo chmod +x /usr/local/bin/kubectl
   25  kubectl 
   26  ssh-keygen -f .ssh/id_rsa
   27  ssh-keygen -f /dev/id_rsa
   28  sudo ssh-keygen -f .ssh/id_rsa
   29  sudo ssh-keygen -f /dev/id_rsa
   30  ls
   31  ls -a
   32  pwd
   33  sudo ssh-keygen -f /home/dev/id_rsa
   34  ssh-keygen -f /home/dev/id_rsa
   35  mkdir id_rsa
   36  ssh-keygen -f /home/dev/id_rsa
   37  ls
   38  cd /home/
   39  ls
   40  pwd
   41  ssh-keygen -f /ubu/home/dev/id_rsa
   42  cd /home/ubu/dev/id_rsa/
   43  cd ..
   44  ssh-keygen -f /home/ubu/dev/id_rsa
   45  ls
   46  cat ./id_rsa/
   47  cat ./id_rsa
   48  cat ./id_rsa.pub
   49  cat ./id_rsa/id_rsa.pub
   50  cd id_rsa/
   51  ls
   52  cd ..
   53  rm -r id_rsa/
   54  ssh-keygen -f /home/ubu/dev/id_rsa
   55  ls -al
   56  cat ./id_rsa.pub
   57  cat ./id_rsa
   58  sudo mv /usr/local/bin/kops-linux-amd64 /usr/local/bin/kops
   59  kops create cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=ap-south-1 --node-count=2 --node--size=t2.micro --dns-zone=k8s-rukjaana.com
   60  kops create cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=ap-south-1 --node-count=2 --node-size=t2.micro --dns-zone=k8s-rukjaana.com
   61  kops create cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=ap-south-1 --node-count=2 --node-size=t2.micro --master-size=t2.micro  --dns-zone=k8s-rukjaana.com
   62  kops create cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=ap-southeast-1 --node-count=2 --node-size=t2.micro --master-size=t2.micro  --dns-zone=k8s-rukjaana.com
   63  kops create cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=us-east-1 --node-count=2 --node-size=t2.micro --master-size=t2.micro  --dns-zone=k8s-rukjaana.com
   64  aws ec2 describe-availability-zones --region eu-central-1
   65  aws ec2 describe-availability-zones --region ap-south-1
   66  kops create cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=us-east-1a --node-count=2 --node-size=t2.micro --master-size=t2.micro  --dns-zone=k8s-rukjaana.com
   67  cd ~/.ssh/
   68  ssh-keygen -f ~/.ssh/id_rsa
   69  ls
   70  kops create cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=us-east-1a --node-count=2 --node-size=t2.micro --master-size=t2.micro  --dns-zone=k8s-rukjaana.com
   71  kops update cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=us-east-1a --node-count=2 --node-size=t2.micro --master-size=t2.micro  --dns-zone=k8s-rukjaana.com
   72  kops update cluster
   73  kops create cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=ap-south-1a --node-count=2 --node-size=t2.micro --master-size=t2.micro  --dns-zone=k8s-rukjaana.com
   74  kops delete cluster --name=k8s.rukjaana.com
   75  kops delete cluster --name=k8s.rukjaana.com --state=s3://kops-state-759
   76  kops delete cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --yes
   77  kops create cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=ap-south-1a --node-count=2 --node-size=t2.micro --master-size=t2.micro  --dns-zone=k8s-rukjaana.com
   78  kops create cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=ap-south-1a --node-count=2 --node-size=t2.micro --master-size=t2.micro  --dns-zone=k8s.rukjaana.com
   79  kops delete cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --yes
   80  kops create cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=ap-south-1a --node-count=2 --node-size=t2.micro --master-size=t2.micro  --dns-zone=k8s.rukjaana.com
   81  kops edit cluster --name=k8s.rukjaana.com --state=s3://kops-state-759
   82  kops update cluster --name=k8s.rukjaana.com --state=s3://kops-state-759
   83  kops update cluster --name=k8s.rukjaana.com --yes --state=s3://kops-state-759
   84  kubectl get nodes
   85  kubectl get nodes ip
   86  kubectl get ip
   87  kubectl get --help
   88  kops edit cluster --name=k8s.rukjaana.com --state=s3://kops-state-759
   89  kops delete cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --yes
   90  kops create cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=ap-south-1a --node-count=1 --node-size=t2.micro --master-size=t2.micro  --dns-zone=k8s.rukjaana.com
   91  kops update cluster --name=k8s.rukjaana.com --yes --state=s3://kops-state-759
   92  kubectl get nodes
   93  kubectl get services
   94  kubectl get nodes --show-labels
   95  history


      22  ls
   23  sudo mv kubectl /usr/local/bin/
   24  sudo chmod +x /usr/local/bin/kubectl
   25  kubectl 
   26  ssh-keygen -f .ssh/id_rsa
   27  ssh-keygen -f /dev/id_rsa
   28  sudo ssh-keygen -f .ssh/id_rsa
   29  sudo ssh-keygen -f /dev/id_rsa
   30  ls
   31  ls -a
   32  pwd
   33  sudo ssh-keygen -f /home/dev/id_rsa
   34  ssh-keygen -f /home/dev/id_rsa
   35  mkdir id_rsa
   36  ssh-keygen -f /home/dev/id_rsa
   37  ls
   38  cd /home/
   39  ls
   40  pwd
   41  ssh-keygen -f /ubu/home/dev/id_rsa
   42  cd /home/ubu/dev/id_rsa/
   43  cd ..
   44  ssh-keygen -f /home/ubu/dev/id_rsa
   45  ls
   46  cat ./id_rsa/
   47  cat ./id_rsa
   48  cat ./id_rsa.pub
   49  cat ./id_rsa/id_rsa.pub
   50  cd id_rsa/
   51  ls
   52  cd ..
   53  rm -r id_rsa/
   54  ssh-keygen -f /home/ubu/dev/id_rsa
   55  ls -al
   56  cat ./id_rsa.pub
   57  cat ./id_rsa
   58  sudo mv /usr/local/bin/kops-linux-amd64 /usr/local/bin/kops
   59  kops create cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=ap-south-1 --node-count=2 --node--size=t2.micro --dns-zone=k8s-rukjaana.com
   60  kops create cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=ap-south-1 --node-count=2 --node-size=t2.micro --dns-zone=k8s-rukjaana.com
   61  kops create cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=ap-south-1 --node-count=2 --node-size=t2.micro --master-size=t2.micro  --dns-zone=k8s-rukjaana.com
   62  kops create cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=ap-southeast-1 --node-count=2 --node-size=t2.micro --master-size=t2.micro  --dns-zone=k8s-rukjaana.com
   63  kops create cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=us-east-1 --node-count=2 --node-size=t2.micro --master-size=t2.micro  --dns-zone=k8s-rukjaana.com
   64  aws ec2 describe-availability-zones --region eu-central-1
   65  aws ec2 describe-availability-zones --region ap-south-1
   66  kops create cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=us-east-1a --node-count=2 --node-size=t2.micro --master-size=t2.micro  --dns-zone=k8s-rukjaana.com
   67  cd ~/.ssh/
   68  ssh-keygen -f ~/.ssh/id_rsa
   69  ls
   70  kops create cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=us-east-1a --node-count=2 --node-size=t2.micro --master-size=t2.micro  --dns-zone=k8s-rukjaana.com
   71  kops update cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=us-east-1a --node-count=2 --node-size=t2.micro --master-size=t2.micro  --dns-zone=k8s-rukjaana.com
   72  kops update cluster
   73  kops create cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=ap-south-1a --node-count=2 --node-size=t2.micro --master-size=t2.micro  --dns-zone=k8s-rukjaana.com
   74  kops delete cluster --name=k8s.rukjaana.com
   75  kops delete cluster --name=k8s.rukjaana.com --state=s3://kops-state-759
   76  kops delete cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --yes
   77  kops create cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=ap-south-1a --node-count=2 --node-size=t2.micro --master-size=t2.micro  --dns-zone=k8s-rukjaana.com
   78  kops create cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=ap-south-1a --node-count=2 --node-size=t2.micro --master-size=t2.micro  --dns-zone=k8s.rukjaana.com
   79  kops delete cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --yes
   80  kops create cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=ap-south-1a --node-count=2 --node-size=t2.micro --master-size=t2.micro  --dns-zone=k8s.rukjaana.com
   81  kops edit cluster --name=k8s.rukjaana.com --state=s3://kops-state-759
   82  kops update cluster --name=k8s.rukjaana.com --state=s3://kops-state-759
   83  kops update cluster --name=k8s.rukjaana.com --yes --state=s3://kops-state-759
   84  kubectl get nodes
   85  kubectl get nodes ip
   86  kubectl get ip
   87  kubectl get --help
   88  kops edit cluster --name=k8s.rukjaana.com --state=s3://kops-state-759
   89  kops delete cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --yes
   90  kops create cluster --name=k8s.rukjaana.com --state=s3://kops-state-759 --zones=ap-south-1a --node-count=1 --node-size=t2.micro --master-size=t2.micro  --dns-zone=k8s.rukjaana.com
   91  kops update cluster --name=k8s.rukjaana.com --yes --state=s3://kops-state-759
   92  kubectl get nodes
   93  kubectl get services
   94  kubectl get nodes --show-labels
   95  history
   96  cd /home/ubu/dev/
   97  ls
   98  mkdir
   99  mkdir git-k8s-copy
  100  cd git-k8s-copy/
  101  git clone https://github.com/wardviaene/kubernetes-course.git
  102  code .
  103  cd ..
  104  ls
  105  cd K8s-deploy/
  106  ls
  107  cd wordpress
  108  ls
  109  cd ..
  110  aws ec2 describe-availability-zones --region ap-south-1
  111  s
  112  ls
  113  cd wordpress-volumes/
  114  ls
  115  aws efs create-file-system --creation-token 2
  116  aws configure
  117  aws efs create-file-system --creation-token 2
  118  aws efs create-mount-target --file-system-id fs-e2887933 --subnet-id subnet-02f5eea5c609231e6 --security-groups sg-0faa51b5c5a425d1c
  119  cd ..
  120  kubectl create wordpress-volumes/
  121  kubectl create -h
  122  kubectl create -f wordpress-volumes/
  123  kubectl get pods
  124  kubectl describe pods
  125  kubectl dlogs pods
  126  kubectl logs pods
  127  kubectl create -f wordpress-volumes/
  128  kubectl get service
  129  get services wordpress-web-service.
  130  kubectlget services wordpress-web-service.
  131  kubectl get services wordpress-web-service.
  132  kubectl get services wordpress-web-service
  133  kubectl get services wordpress-web-service.yml
  134  kubectl get wordpress-web-service.yml
  135  ls
  136  cd wordpress-volumes/
  137  kubectl create wordpress-web-service.yml
  138  kubectl create /wordpress-web-service.yml
  139  kubectl create ./wordpress-web-service.yml
  140  ls
  141  kubectl create wordpress-web-service.yml
  142  kubectl create -f wordpress-web-service.yml
  143  kubectl get services wordpress
  144  kubectl delete services wordpress
  145  kubectl create -f wordpress-web-service.yml
  146  kubectl get services wordpress
  147  kubectl discribe  services wordpress
  148  kubectl describe services wordpress
  149  cd ..
  150  kubectl delete -f wordpress-volumes/
  151  kubectl wordpress-volumes/
  152  ls
  153  cd wordpress-volumes/
  154  ls
  155  kubectl create -f storage.yml
  156  kubectl create -f pv-claim.yml 
  157  ls
  158  kubectl create -f wordpress-secrets.yml 
  159  kubectl create -f wordpress-db.yml 
  160  kubectl create-f wordpress-db-service.yml 
  161  kubectl create -f wordpress-db-service.yml 
  162  kubectl get pv
  163  kubectl get pods
  164  kubectl create -f wordpress-web.yml 
  165  kubectl create -f wordpress-web-service.yml 
  166  kubectl get services wordpress
  167  kubectl logs services wordpress
  168  kubectl describe services wordpress
  169  kubectl describe services wordpres
  170  kubectl logs services wordpress
  171  kubectl describe services wordpres
  172  kubectl logs services wordpress
  173  kubectl get services wordpress
  174  kubectl delete -f wordpress-web-service.yml 
  175  kubectl create -f wordpress-web-service.yml 
  176  kubectl get services wordpress
  177  kubectl describe services wordpres
  178  kubectl delete -f wordpress-web-service.yml 
  179  kubectl create -f wordpress-web-service.yml 
  180  kubectl get services wordpress
  181  kubectl describe services wordpres
  182  kubectl delete -f wordpress-web-service.yml 
  183  kubectl create -f wordpress-web-service.yml 
  184  kubectl describe services wordpres
  185  kubectl get pods
  186  kubectl delete wordpress-db-tfqj4
  187  kubectl kill wordpress-db-tfqj4
  188  kubectl kill pod wordpress-db-tfqj4
  189  kubectl delete pod wordpress-db-tfqj4
  190  kubectl get pods
  191  kubectl delete wordpress-deployment-7bfd9bb9df-dfn85
  192  kubectl delete pod/wordpress-deployment-7bfd9bb9df-dfn85
  193  kubectl get pods
  194  kubectl delete pod/wordpress-deployment-7bfd9bb9df-dfn85
  195  kubectl delete pod/wordpress-deployment-7bfd9bb9df-scs8g
  196  ls
  197  kubectl delete -f wordpress-web.yml 
  198  kubectl create -f wordpress-web.yml 
  199  kubectl get pods
  200  kubectl delete -f wordpress-web.yml 
  201  kubectl create -f wordpress-web.yml 
  202  kubectl get pods
  203  kubectl delete -f wordpress-web.yml 
  204  kubectl create -f wordpress-web.yml 
  205  kubectl get pods
  206  kubectl delete -f wordpress-web.yml 
  207  kubectl create -f wordpress-web.yml 
  208  kubectl get pods
  209  kubectl delete -f wordpress-web.yml 
  210  kubectl create -f wordpress-web.yml 
  211  history
ubu@ubu:~/dev/K

 1  docker
    2  sudo apt  install docker.io
    3  sudo docker
    4  docker
    5  docker images
    6  sudo docker images
    7  histry
    8  history
    9  aws ec2 describe-instance | grep subnet
   10  aws ec2 describe-instances | grep subnet
   11  aws ec2 describe-instances
   12  aws ec2 describe-instances | grep SubentId
   13  aws ec2 describe-instances | grep Subent
   14  aws ec2 describe-instances
   15  history



