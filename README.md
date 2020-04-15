# Personal Info

Name: Donglin Yang (杨东霖）

Education: University of Regina, 2010 - 2013 (Electronic Engineering) (dropped out)

Github: https://github.com/Krysme

# Contact Info

Cell: `15072869578`

Email: `332407470@qq.com`

Matrix Account: `@yangdonglin:www.yangdonglin2020.xyz`





# Skill Set
## Experience with Rust 
###  Hobby Project (Almost finished)
[https://github.com/Krysme/greater-fire](https://github.com/Krysme/greater-fire)

A re-write attempt for [trojan](https://github.com/trojan-gfw/trojan). With rust's `async & await`, I believe that the implementation of trojan can be 
simplified in a great scale. The original `trojan` is implemented in C++ with `boost::asio`.Since C++ does not have `coroutines` yet (at least not 
before C++ 20 gets widely adopted), it has to be implemented with callbacks and state-machines. And I believe it is possible to be re-written in rust 
in less than 1000 lines of code. Through this project I'm more familiar with the new `async-await` feature.


  
### Personal Contract Project
An proprietary system for automatic plant watering, running rust code on ARM linux, communicating with the server with the `MQTT` 
protocol. This projcet involves interacting with an `MQTT` C library, since we don't have a matured one in the rust eco-system yet. It basically 
receives watering schedule or one-shot operation from the server and takes action.


### Misc
And also, I've answered some `知乎` questions， and here are the link of answers which might reflect some of my understanding of `rust` and `C++`.

[知乎](https://www.zhihu.com/people/krys-1998/answers)


## Understanding of Blockchain/DLT(Distributed Ledger Tech)

### How I get to understand blockchain
* I'm a follower of `Andreas M. Antonopoulos` on youtube
* I'm currently learning from `MIT open courseware` on 
[this playlist](https://www.youtube.com/watch?v=IJquEYhiq_U&list=PLUl4u3cNGP61KHzhg3JIJdK08JLSlcLId)
* I have also briefly read the white paper of `Swirlds's Hashgraph` and `Maidsafe's Parsec`,
because I believe these new consensus mechanisms (which achieves ABFT) with better efficiency might 
resolve the scalability issues that currently bitcoin (or other blockchain based currencies) faces.







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
`javascript` in `node.js` with `express`.


### Job Description
* Architecture design for all products.
* Technical training for new members.
* Communication with clients and other departments for feature requests.
* Team management and leadership


## Principal Engineer 2017.11 - Now ([STAr Technologies(Wuhan)](http://www.star-quest.com))
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


