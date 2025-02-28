Comando para profile 'guru' no aws cli

aws ec2 create-key-pair --key-name MinhaKeyPair --query 'KeyMaterial' --output text --profile guru > MinhaKeyPair.pem
