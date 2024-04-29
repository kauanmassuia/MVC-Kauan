# MVC-Kauan

VIEW:
- Cadastro: Está presente como uma interação com o usuário
- Login: Está presente como uma interação com o usuário
- Feedback do grupo: Visualização do grupo
- Questionário de perfil: Está presente como uma interação com o usuário
- Medidor de felicidade: Está presente como uma interação com o usuário
- Perfil de integrante: Está presente como uma interação com o usuário e visualização do grupo

CONTROLLERS:
- Users Player: Exibe, grava e procura.
- User Tutor: Visualiza, grava e procura.
- Feedback: Grava, visualiza e procura.
- Perfil: Grava e visualiza.
- Nível de felicidade: Grava, visualiza e calcula.
- Integrante: Visualiza e procura

Models:
- User player: Id, nome, país, id_time, email, senha.
- User tutor: id, nome, país, id_times, email, senha.
- Feedbacks: user_destino, user_realizdor, conteudo_feedback.
- Perfil: perfil_de_lideranca, respostas_questionario.
- Nível de Felicidade: porcentagem_individual, porcentagens_grupo
- Integrante: id, nome, país, porcentagem_felicidade, habilidades.

