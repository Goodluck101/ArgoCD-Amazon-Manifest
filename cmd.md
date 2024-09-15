 1844  ls
 1845  cd ../../../~
 1846  cd ../../..
 1847  cd ~
 1848  ls
 1849  curl -sLO "https://github.com/eksctl-io/eksctl/releases/download/v0.188.0/eksctl_Linux_amd64.tar.gz"
 1850  ls
 1851  ls -ltra
 1852  ls
 1853  date
 1854  sudo apt-get update
 1855  sudo apt-get install --reinstall ca-certificates
 1856  sudo apt-get update
 1857  sudo apt-get install wget
 1858  export http_proxy="http://yourproxy:port"
 1859  export https_proxy="http://yourproxy:port"
 1860  ls
 1861  wget -O /tmp/eksctl.tar.gz "https://github.com/weaveworks/eksctl/releases/latest/download/eksctl_$(uname -s)_amd64.tar.gz"
 1862  unset http_proxy
 1863  unset https_proxy
 1864  unset http_proxy
 1865  wget -O /tmp/eksctl.tar.gz "https://github.com/weaveworks/eksctl/releases/latest/download/eksctl_$(uname -s)_amd64.tar.gz"
 1866  echo $PLATFORM
 1867  [Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12
 1868  curl -sLO "https://github.com/eksctl-io/eksctl/releases/latest/download/eksctl_$PLATFORM.tar.gz"
 1869  ls
 1870  curl -sL "https://github.com/eksctl-io/eksctl/releases/latest/download/eksctl_checksums.txt" | grep $PLATFORM | sha256sum --check
 1871  tar -xzf eksctl_$PLATFORM.tar.gz -C /tmp && rm eksctl_$PLATFORM.tar.gz
 1872  rm eksctl_.tar.gz
 1873  ls
 1874  echo $PLATFORM
 1875  ARCH=amd64
 1876  PLATFORM=$(uname -s)_$ARCH
 1877  echo $PLATFORM
 1878  curl -sLO "https://github.com/eksctl-io/eksctl/releases/latest/download/eksctl_$PLATFORM.tar.gz"
 1879  ls
 1880  curl -sL "https://github.com/eksctl-io/eksctl/releases/latest/download/eksctl_checksums.txt" | grep $PLATFORM | sha256sum --check
 1881  tar -xzf eksctl_$PLATFORM.tar.gz -C /tmp && rm eksctl_$PLATFORM.tar.gz
 1882  sudo mv /tmp/eksctl /usr/local/bin
 1883  eksctl
 1884  eksctl version
 1885  ifconfig
 1886  kubectl
 1887  clear
 1888  aws configure
 1889  eksctl create cluster --name goody-k8s --region us-east-1
 1890  kubectl version
 1891  curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"
 1892  kubectl version
 1893  sudo nano ~/.kube/config
 1894  chmod +x kubectl
 1895  ls
 1896  sudo mv kubectl /usr/local/bin/
 1897  ls
 1898  ls /usr/local/bin
 1899  kubectl version
 1900  sudo nano ~/.kube/config
 1901  kubectl version
 1902  sudo nano ~/.kube/config
 1903  kubectl version
 1904  sudo nano ~/.kube/config
 1905  kubectl version
 1906  sudo nano ~/.kube/config
 1907  kubectl version
 1908  kubectl get nodes
 1909  aws eks update-kubeconfig --name goody-k8s --region us-east-1
 1910  sudo nano ~/.kube/config
 1911  kubectl get nodes
 1912  sudo nano ~/.kube/config
 1913  kubectl get nodes
 1914  aws eks update-kubeconfig --name goody-k8s --region us-east-1
 1915  sudo nano ~/.kube/config
 1916  kubectl get nodes
 1917  aws eks update-kubeconfig --name goody-k8s --region us-east-1
 1918  curl -o aws-iam-authenticator https://amazon-eks.s3.us-west-2.amazonaws.com/latest/2022-06-29/bin/linux/amd64/aws-iam-authenticator
 1919  chmod +x ./aws-iam-authenticator
 1920  mv ./aws-iam-authenticator /usr/local/bin/
 1921  sudo mv ./aws-iam-authenticator /usr/local/bin/
 1922  kubectl get nodes
 1923  curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"
 1924  chmod +x ./kubectl
 1925  sudo mv ./kubectl /usr/local/bin/kubectl
 1926  kubectl get nodes
 1927  sudo nano ~/.kube/config
 1928  kubectl get nodes
 1929  sudo apt-get update && sudo apt-get install -y kubectl
 1930  kubectl get nodes
 1931  rm -rf ~/.kube/cache
 1932  kubectl get nodes
 1933  aws eks update-kubeconfig --name goody-k8s --region us-east-1
 1934  kubectl get nodes
 1935  rm -rf ~/.kube/cache
 1936  kubectl get nodes
 1937  sudo nano ~/.kube/config
 1938  restart
 1939  rstart
 1940  sudo apt install x11-session-utils
 1941  rstart
 1942  reboot
 1943  sudo reboot
 1944  sudo nano ~/.kube/config
 1945  kubectl get nodes
 1946  sudo nano ~/.kube/config
 1947  kubectl get nodes
 1948  sudo nano ~/.kube/config
 1949  kubectl get nodes
 1950  sudo nano ~/.kube/config
 1951  kubectl get nodes
 1952  curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
 1953  unzip awscliv2.zip
 1954  sudo ./aws/install --update
 1955  aws --version
 1956  kubectl get nodes
 1957  sudo nano ~/.kube/config
 1958  kubectl get all
 1959  kubectl cluster-info
 1960  kubectl cluster-info dump
 1961  ls
 1962  kubectl cluster-info dump > file1
 1963  sudo nano file1
 1964  mv file1 k8s-cluster-info
 1965  ls
 1966  kubectl get pods
 1967  kubectl get pods -A
 1968  kubectl get namespaces
 1969  kubectl get pods --all-namespaces
 1970  kubectl get ns
 1971  ls -ltra
 1972  cd /usr/local/bin
 1973  ls
 1974  cd ../../..
 1975  cd ~
 1976  ls'
 1977  ls
 1978  git clone https://github.com/ooghenekaro/argocd-amazon-manifest.git
 1979  ls
 1980  cd argocd-amazon-manifest/
 1981  ls
 1982  git init
 1983  git commit -m "first k8s deployment"
 1984  git branch -M main
 1985  git remote set-url origin https://github.com/Goodluck101/aws-k8s-first-deployment.git
 1986  git push -u origin main
 1987  ls
 1988  sudo nano deployment.yml 
 1989  git status
 1990  git add .
 1991  git commit -m "modified the deployment file"
 1992  git push -u origin main
 1993  sudo nano deployment.yml 
 1994  kubectl apply -f deployment.yml 
 1995  kubectl get pods
 1996  kubectl logs amazon-deployment-c4456d65c-4gmgr
 1997  kubectl get pods
 1998  kubectl describe pod amazon-deployment-c4456d65c-4gmgr
 1999  kubectl get pods
 2000  ls
 2001  cd argocd-amazon-manifest/
 2002  kubectl get pods
 2003  ls
 2004  sudo nano deployment.yml 
 2005  kubectl apply -f deployment.yml 
 2006  kubectl get pods
 2007  sudo nano deployment.yml 
 2008  clear
 2009  sudo nano deployment.yml 
 2010  kubectl apply -f deployment.yml 
 2011  kubectl get pods
 2012  ls
 2013  nano README.md 
 2014  sudo nano deployment.yml 
 2015  kubectl apply -f deployment.yml 
 2016  kubectl get pods
 2017  kubectl describe pods amazon-deployment-69b8d9d7b7-6wjlw
 2018  sudo nano deployment.yml
 2019  kubectl apply -f deployment.yml
 2020  sudo nano deployment.yml
 2021  kubectl apply -f deployment.yml
 2022  ls
 2023  kubectl get pods
 2024  kubectl get deployments
 2025  kubectl delete deployment amazon-deployment
 2026  kubectl apply -f deployment.yml
 2027  kubectl get pods
 2028  ls
 2029  sudo nano deployment.yml
 2030  kubectl apply -f deployment.yml
 2031  kubectl get pods
 2032  sudo nano deployment.yml
 2033  kubectl apply -f deployment.yml
 2034  kubectl get pods
 2035  kubectl get pods -A
 2036  kubectl get -A
 2037  kubectl get all
 2038  ls
 2039  touch cmd
 2040  ls
 2041  history 100 > cmd
 2042  nano cmd
 2043  history 200 > cmd
