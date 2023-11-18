1 สร้าง database ของเราใน localphpmyadmin
2 สร้าง folder fullstack-node
3 สร้าง directory ใหม่ขึ้นมาใน directory ของ fullstack-node เป็น backend และ npm init
4 ใช้ code . ใน terminal เพื่อที่เราจะเข้าไปแก้ไข code และเข้า google Express cors middleware เพื่อเอา script ไปใส่ใน index.js เมื่อนำไปใส่แล้ว เข้า terminal เพื่อ install express cors ใช้ command => npm install express cors
5 ใช้ nodemon --name ใช้ในการรัน * หากไม่มี nodemon use command => npm install -g nodemon , npm install --save-dev nodemon
6 นำไปเชื่อ database ตอนนี้ใช่ node mysql2 , ref => // https://www.npmjs.com/package/mysql2
7 สร้าง .env ขึ้นมาเพื่อเก็บ database user,database,password , ref => // https://www.npmjs.com/package/dotenv
