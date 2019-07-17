---
layout: post
title:  "Minikube with kvm"
date:   2019-07-17 08:59:34 +0200
categories: kubernetes vm container cloud native
---

In the first place, you need to install Kubectl

{% highlight shell %}
sudo apt-get update && sudo apt-get install -y apt-transport-https
curl -s https://packages.cloud.google.com/apt/doc/apt-key.gpg | sudo apt-key add -
echo "deb https://apt.kubernetes.io/ kubernetes-xenial main" | sudo tee -a /etc/apt/sources.list.d/kubernetes.list
sudo apt-get update
sudo apt-get install -y kubectl
{% endhighlight %}
