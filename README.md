# Personal Info

Name: Donglin Yang (杨东霖）

Education: University of Regina, 2010 - 2013 (Electronic Engineering) (dropped out)

Github: https://github.com/Krysme


# Skill Set: 
* Experience with Rust , C++, and some light experience with wonderful languages like Clojure, Typescript etc.
* Familiarity with the GNU/Linux Operating System (I use Arch for my own desktop).
* Some encounter of GPU programming, `CUDA` specifically, from a crypto mining project.
* I'm also a fast learner of new technologies.

# Recent Projects involved


## A Proprietary Fork for the Filecoin Node
[lotus](https://github.com/filecoin-project/lotus) is the official node implementation for filecoin with a sub-optimal mining efficiency. So I forked 
it's rust library to have some of my own optimizations to provide a proprietary grade mining service for the clients of my employer. My own 
implementation of lotus has a clear advantage on both time and memory usage, especially when it comes to the execution time of the zk-snark proving 
algorithm of filecoin.

## Personal Contract Project
An proprietary system for automatic plant watering, running rust code on ARM linux, communicating with the server with the `MQTT` 
protocol. This projcet involves interacting with an `MQTT` C library, since we don't have a matured one in the rust eco-system yet. It basically 
receives watering schedule or one-shot operation from the server and takes action.

##  Hobby Project (Almost finished)
[https://github.com/Krysme/greater-fire](https://github.com/Krysme/greater-fire)

A re-write attempt for [trojan](https://github.com/trojan-gfw/trojan). With rust's `async & await`, I believe that the implementation of trojan can be 
simplified in a great scale. The original `trojan` is implemented in C++ with `boost::asio`.Since C++ does not have `coroutines` yet (at least not 
before C++ 20 gets widely adopted), it has to be implemented with callbacks and state-machines. And I believe it is possible to be re-written in rust 
in less than 1000 lines of code. Through this project I'm more familiar with the new `async-await` feature.
  


# Misc
Also, I've answered some `知乎` questions， and here are the link of answers which might reflect some of my understanding of `rust` and `C++`.

[知乎](https://www.zhihu.com/people/krys-1998/answers)




# Working Experience

## System Engineer 2014.8 - 2015.7 (广西支付通商务服务有限公司）
### Abstract
We have a payment processing system running in clustered redhat linux, with nginx (as the reverse proxy) & tomcat and the database is IBM DB2.

### Job Description
* Responsible for the maintainance job of the backend of the payment system.
* Trouble shooting and assisting the main developers.
* System administration.

## C++ Junior Developer 2015.7 - 2016.2 (上海新跃物流企业管理有限公司）
### Abstract
In this job, I'm responsible for the client application of a voip calling system developed with WxWidget. The app interacts with the server to 
make/transfer calls and log customer complains.

### Job Description
* Client side software development & bug fixing.
* Communication with other department for feature requests.
* Trouble shooting for server side software deployment.


## Technical Leader 2016.2 - 2017.11 (上海慎独信息科技有限公司）
### Abstract
This is a startup company with less than 10 employees, and my role was the tech lead for the development of our software products which help 
our manufacturing bussiness clients monitor and improve the efficiency of their employees.

### Technical Details
The software are designed to have a client - server architecture. The client is built with `Qt` and `boost`, and we have a server written in 
`javascript` with the `node.js` runtime.


### Job Description
* Architecture design for all products.
* Technical training for new members.
* Communication with clients and other departments for feature requests.
* Team management and leadership


## Principal Engineer 2017.11 - 2020.5 ([STAr Technologies(Wuhan)](http://www.star-quest.com))
### Abstract
STAr Technologies develops semi-conductor testing solutions and probe cards, and the department I lead is in charge of the `Sagittarius` product 
series. [This link](http://www.star-quest.com/products01_a.php?mode=&xs_id=001&class_sn=152) demostrates detailed information about this series of
products. 

### Technical Details
`Sagittarius` is a multi-process solution which uses IPC exclusively. A fraction of it is written in rust, but mostly in C++.


### Job Description
* Project management.
* Architecture design.
* Periodical training & skill sharing.
* Communication with clients and other departments for specification of the software.
* Team management and leadership
* Communication with India branch (in English) for cooperation and job distribution for both Wuhan & India branch.


## Rust Developer (星际无限/神算云科技)2020.9 - 2022.11
### Abstract
I'm the only rust developer in this company, and involved with anything related to system programming including:
1. Crypto mining software optimization (mainly).
2. Bug fixing and stability improvement for the mining operation.
3. Developing a crypto wallet which interfaces with the hardware.


### Technical Details
The optimized version of the mining software takes advantage of:
1. Implementing a better implemented zk-snark scheme,
2. Offloading some of the highly parallelized tasks to the GPU,
3. Take advantage of the hardware's topology by having a better CPU affinity setup, and
4. Use multi-threaded computation for CPU tasks to make use of the server CPUs as much as possible.


## Rust Developer (北醌云超算) 2022.12 - now
### Abstract
I'm in charge of a remote desktop project for client to operate on the cloud computers.
Rsponsibilities including:
1. The backend implementation of the software.
2. Optimization for a lower latency and less CPU/Memory usage.
3. Find inspirations by investigating similar open source solutions (like RustDesk).


### Technical Details
This project takes the advantage of WebRTC to stream video feed from the cloud to the client side
in real time. and perform mouse/keyboard operations sent by the user.
The backend is written in rust mainly, with some FFI with C libraries like `ffmpeg`.
The frontend is an `electron` based app for current version. A more performant rendering schem (like directly
render image buffers with `wgpu`) might be used in future releases.


