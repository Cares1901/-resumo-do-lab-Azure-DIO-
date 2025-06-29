# Lab 02 - Resumo de Máquinas Virtuais (VM's) no AZURE

As máquinas virtuais (VM) do Azure podem ser criadas por meio do Portal do Azure. 
Esse método fornece uma interface de usuário baseada em navegador para criar as VMS seus recursos relacionados. 
Esse início rápido mostra como usar o portal do Azure para implantar uma máquina virtual (VM) no Azure que executa o Windows Server 2022 Datacenter. 
Para ver a VM em ação, você habilita o protocolo RDP na VM e instala o servidor Web do IIS.

# Passo a Passo Criação de Máquina Virtual:
1. Fazer Login na Conta da Azure
2. Serviços >> Máquinas Virtuais >> Criar
3. Definir o grupo de recursos, Nomear a VM e escolher qual tipo de VM (Windows, Linux).
4. Defina Região e Disponibilidade.
5. Selecione as zonas.
![image](https://github.com/user-attachments/assets/0bcec434-1420-45f9-b8ba-f83005903af9)


6. Aplique o tipo de Segurança, Defina a Arquitetura da VM e o tamanho da VM.
![image](https://github.com/user-attachments/assets/240475a9-5ebc-4b1c-bc38-e3f4291590e7)


7. Em Conta de administrador, forneça um nome de usuário e uma senha. 
A senha deve ter no mínimo 12 caracteres e atender a requisitos de complexidade definidos.
![image](https://github.com/user-attachments/assets/948ae0af-5572-429a-b00c-36809d790d66)

8. Em Regras de porta de entrada, escolha Permitir portas selecionadas. 
Em seguida, selecione RDP (3389) e HTTP (80) na lista suspensa.
9. Revise e selecione "Revisar+Criar".
![image](https://github.com/user-attachments/assets/53a649c2-79d3-4738-93a6-c52fc58b78c5)

10. Após a validação ficar com o ícone verde, selecione "Criar. 
Após criado, acesse a VM através do ícone "Ir para o Recurso."

# SLA - Azure
Quantos mais "9", menor será o tempo de inatividade da nuvem. 
![image](https://github.com/user-attachments/assets/e396cfc8-cedf-4f78-8e2b-ed3432227f1d)

