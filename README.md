### Hi, Im Lucas Casemiro
# __Welcome to my GitHub!__

📍   __Florianópolis - Brazil__   📍  
📚 __.__ Learning __HTML__ and __CSS__

👨‍🎓 __.__ Currently coursing the 11th grade at SENAI Technical Education in __Systems Development__

🗽 __.__ __Upper-Intermediate__ English

import requests

url = "https://api.github.com/repos/:owner/:repo"
headers = {"Authorization": "Bearer SEU_TOKEN_DE_ACESSO"}

response = requests.get(url, headers=headers)

if response.status_code == 200:
    repo_data = response.json()
    # Faça algo com os dados do repositório
else:
    print(f"Erro na solicitação: {response.status_code}")


![gif](https://media.tenor.com/2HuG5tLOLqMAAAAi/rotating-cheese.gif)
