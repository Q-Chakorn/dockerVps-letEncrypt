# dockerVps-letEncrypt
 
 อ้างอิงจาก 
 https://blog.pjjop.org/how-to-config-vps-and-letsencrypt-with-docker-container/

 ในส่วน let encrypt หรือการขอใบ cert จำเป็นจะต้องมี่ Domain Name
 **cert let encrypt จะต้องต่ออายุทุก 3 เดือน

--help--
 ** 1.ในกรณี multi user บนเครื่องเดียวกัน การตั้งชื่อ folder and container_name ไม่ควรซ้ำกัน 
 ** 2.หรือจะใช้ docker-compose -p <project name> up -d โดยไม่ต้องระบุ container name ใน docker-compose.yaml
 ** 3.สร้าง file env แล้วใส่ COMPOSE_PROJECT_NAME=<name> โดยไม่ต้องระบุ container name ใน docker-compose.yaml