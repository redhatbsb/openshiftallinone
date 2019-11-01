# Openshift All in One
Sobe uma instancia Openshift All-In-One na AWS em 25 min.  

# Exemplo de config.yml
\# ========================
\# Configuracoes essenciais
provider: aws  

\# ========================  
\# Configuracoes GCE  
\# ========================  
\#  
credentials_file: /home/user/path/to/service.json  
chave_ssh_gce: /home/user/path/to/ssh_private_key
usuario_ssh_gce: user
 
  
\# ========================  
\# Configuracoes AWS  
\# ========================  
aws_access_key: ASDASDASAASDA  
aws_secret_key: basdasdasdsadas    
aws_vpc_network: vpc-xyz  
aws_subnet_id: subnet-xyz  
aws_security_group: sg-xyz  
aws_key_name: awskey  
usuario_ssh_aws: centos  
usuario_ssh_aws_rhel: ec2-user  
chave_ssh: /home/user/path/to/private_key    
id_instancia_aws: "AllInOne"  
 
\# ======================== 
\# Configuracoes Subscricao  
\# ========================  
user: userrhn  
password: passrhn  
poolid: 8a85f9996b498098ds90a  
oreg_auth_user: "11529260|whateaver"  
oreg_auth_password: "eyJhbGciOiJSUzUxMiJ9.eyJzdWIiOiI2ZmI1MDkyMGY2ZTc0N2U4YTEzNjIyNjE2ZjlkYzAyMiJ9.nGqt8LzXcjBESdY985_6ie_3Ejvdri4Qm_L9GLyBxhyFQo2uVbOHPw9XOpyHs46JzBVgswYQWDUPCBrarNJAIBLSXuCz_HvygLD7CBjMjXkf_QTVep76sI-hc6MYqqnZ6t7DaxvjTJidj6uNJOIw7Cc3A4WTAW5mkI_2GGWq7Gx4_lDugrafM3NFm7opEJSmw08O1WUXh02-SmErMhAg-mnT3hvghKU_CxI_kGW1K8scjoA7T1IYoIsQBTTEtMhcJ45cbWkWbmU7Q9SkC-jJB59czMQAhq2Eeq92PLxAonjxsf5mSWcG0SFjmkQ42CbW5m6xzf_Uls312T9NyYErRNDRzidBWjuNMBpsDMlJHqdOIc39CVPVx3aNJ7fVoC-RB6g0hn3Pverp6C3WBGMto0FKImvupNACwUGseX1k2zWJDi5LIdGSw1Iswmgnfr7qPtbIzOLwJa6TZtB3xlF-KPU2kwJtiixl8gGNBjpBjZrmnKBn1GUwabC_fg4SFqzfVzeSXgOJaHqRF_RlcolgmSd2d9rniYDN_TNacpGVylm5w7lPvlDy8ktHT3XkDpbrKaaKvYmIJoev"  



