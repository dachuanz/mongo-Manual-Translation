# mongo-Manual-Translation
基于 [Mongodb 手册 英文版 ](http://docs.mongodb.org/manual/)翻译。

**欢迎来到Mongodb 手册。** Mongodb 是易于开发和伸缩的开源，基于文档结构数据库。
>MongoDB使用了BSON这种结构来存储数据和网络数据交换。把这种格式转化成一文档这个概念(Document)，因为BSON是schema-free的，所以在MongoDB中所对应的文档也有这个特征，这里的一个Document也可以理解成关系数据库中的一条记录(Record)，只是这里的Document的变化更丰富一些，如Document可以嵌套。
MongoDB以BSON做为其存储结构的一种重要原因是其可遍历性。



##实例


##入门##

MongoDB提供如下版本的入门指南：
###Mongo Shell##
>Once you have installed and have started MongoDB, connect the mongo shell to your running MongoDB instance. Ensure that MongoDB is running before attempting to launch the mongo shell.

>On the same system where the MongoDB is running, open a terminal window (or a command prompt for Windows) and run the mongo shell with the following command:


###Python 
###Java 
###Node.js 
### C\# ###
###C\+\+
C++ 驱动正在开发中。


##MongoDB CRUD Introduction##
>MongoDB stores data in the form of documents, which are JSON-like field and value pairs. Documents are analogous to structures in programming languages that associate keys with values (e.g. dictionaries, hashes, maps, and associative arrays). Formally, MongoDB documents are BSON documents. BSON is a binary representation of JSON with additional type information. In the documents, the value of a field can be any of the BSON data types, including other documents, arrays, and arrays of documents. For more information, see Documents.

MongoDB存储文档形式的数据。文档形式近似[JSON](http://www.json.org).MongoDB文档正式名称是[BSON](http://docs.mongodb.org/meta-driver/latest/legacy/bson/)文档。
