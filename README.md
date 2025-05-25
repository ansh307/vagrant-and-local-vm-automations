# 🧰 Vagrant Project 

This repository contains a collection of practical **Vagrant projects** that demonstrate a wide range of capabilities — from configuring basic VM resources to provisioning, syncing directories, and automating complex setups like **WordPress installations** and **multi-VM environments**.

---


## 🧰 Prerequisites

- [Vagrant](https://www.vagrantup.com/downloads)
- [VirtualBox](https://www.virtualbox.org/) or another supported provider
- (Optional) Git to clone the repo

---

## 🚀 How to Use

### 🔄 Clone the Repository

```bash
git clone https://github.com/yourusername/vagrant-projects.git
cd vagrant-projects
```

### ▶️ Launch Any Project

Choose a folder and run the following inside it:

```bash
vagrant up
```

### 💻 SSH into a VM

```bash
vagrant ssh
```

### 🛑 Stop the VM

```bash
vagrant halt
```

### 🧹 Destroy the VM

```bash
vagrant destroy -f
```

---

## 🔍 Example Vagrantfile Snippet (IP, RAM, CPU)

```ruby
Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/jammy64"
  config.vm.network "private_network", ip: "192.168.56.10"
  config.vm.provider "virtualbox" do |vb|
    vb.memory = "1024"
    vb.cpus = 2
  end
end
```

---


## 📂 Suggested Use Cases

- Practice DevOps tools & Vagrant workflows  
- Learn infrastructure automation basics  
- Set up repeatable local environments for testing  
- Create a mini-lab for Linux/Vagrant training

---

## 👨‍💻 Author

**Ansh**  

---

