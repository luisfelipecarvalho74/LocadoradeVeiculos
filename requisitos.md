# Engenharia de Requisitos


## Requisitos Funcionais

1. O sistema deve permitir ao usuário realizar cadastro utilizando nome, CPF e senha e login utilizando CPF e senha.  

2. O sistema deve permitir ao usuário escolher a data/hora, qual veículo deseja alugar e se fará o pagamento pelo site ou presencialmente na retirada.

3. O sistema deve permitir que o usuário cancele sua reserva.

4. O sistema deve exibir todos os veículos disponíveis para as datas e locais selecionados.

5. O sistema deve permitir a pesquisa rápida de clientes por nome, CPF ou CNH.

6. O sistema deve permitir ao cliente realizar a cotação de preços informando datas e horários de retirada e devolução.

7. O sistema deve permitir ao cliente selecionar e adicionar itens opcionais (Seguros, cadeirinha de bebê, GPS) à reserva.

8. O sistema deve permitir a criação de uma reserva, bloqueando o veículo no inventário.


## Requisitos Não Funcionais

1. O sistema deve funcionar 24 horas por dia e 7 dias por semana.

2. O sistema deve guardar de forma segura e confidencial os dados dos clientes.

3. O sistema deve ser compatível com diferentes dispositivos e navegadores.

4.  O sistema deve responder de forma rápida às ações do usuário(tempo de resposta de 2 segundos).

5. O sistema deve ter uma interface intuitiva, para que o usuário não tenha dificuldades nas suas ações.


## Regras de Negócio

1. O cliente deve ser maior de 21 anos para alugar um veículo.

2. A reserva só pode ser cancelada com antecedência de 48 horas.

3. O carro só estará disponivel para locação após passar pela vistoria.

4. O locatário deve ter CNH válida à no minímo 2 anos.

5. A locação mínima é de 1 dia.

6. O sistema deve permitir que o cliente realize pagamentos com cartões de crédito, débito e pix.

7. É concedida uma tolerância de 1 hora para devolução do veículo após o horário combinado, após a tolerância de 1 hora, será cobrada uma diária adicional completa.

8. Em caso de não comparecimento do locatário (no-show) sem aviso prévio, a reserva é cancelada e o cliente é cobrado pelo valor da primeira diária ou por uma taxa fixa.
