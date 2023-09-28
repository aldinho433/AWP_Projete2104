# AWP -  AUDIO WATCH PROJECT!!!


## 💻 Sobre o projeto.

 Conhecido como AWP (Audio Watch Project), uma iniciativa inovadora destinada a atender às necessidades específicas das pessoas com deficiência auditiva. Este projeto revolucionário, combina uma avançada tecnologia de sensoriamento sonoro com soluções de comunicação eficazes, proporcionando uma experiência aprimorada para indivíduos que enfrentam desafios na percepção auditiva.

## 💻 Como funciona?

 O sistema opera da seguinte maneira: uma unidade compacta é equipada com microfones posicionados estrategicamente em pontos distribuídos pela residência. Ao detectar um evento sonoro de relevância, como uma campainha ou alarme, os microfones captam o sinal e o transmitem para um relógio inteligente. Este, por sua vez, emite uma vibração perceptível para alertar o indivíduo com deficiência auditiva acerca do evento sonoro. Posteriormente, o usuário do dispositivo poderá verificar a tela do relógio para identificar o ambiente no qual o som foi detectado.


## 💻 Hardware.

Hardware Utilizado:

 Para a implementação do nosso projeto, utilizamos uma série de componentes de hardware aos quais foram essenciais. Entre eles, destacam-se:

1. 2 ESP8266 NodeMCU D1 Mini
   - Descrição: Placas de desenvolvimento baseadas em ESP8266, proporcionando conectividade Wi-Fi.
   
2. 1 Botão Touch
   - Descrição: Componente sensitivo ao toque utilizado para interação do usuário com o sistema.

3. 1 Bateria HJ541112
   - Descrição: Fonte de energia portátil para o dispositivo.

4. 1 Módulo de Vibração Motor DC PWM (NFE)**
   - Descrição: Componente que gera vibração perceptível para alertar o usuário sobre eventos sonoros.

5. 1 Display OLED 0.96"
   - Descrição: Tela de exibição que fornece informações ao usuário sobre a localização do som.

6. 1 Módulo Sensor Detector de Som (Microfone KY)
   - Descrição: Sensor responsável pela captação e identificação de eventos sonoros.

7. 1 LED 5mm
   - Descrição: Diodo emissor de luz para indicação visual.

8. 1 Resistor de 182 ohm
   - Descrição: Componente que limita a corrente elétrica em determinados pontos do circuito.

9. Fios Jumper Macho-Macho e Macho-Fêmea
   - Descrição: Cabos condutores utilizados para conectar os componentes eletrônicos.

Estes componentes formam a base do hardware empregado para a execução bem-sucedida do projeto. Cada um desempenha um papel crucial no funcionamento do sistema, desde a detecção de sons até a notificação do usuário.

## 💻 Software.

Software:

 No âmbito do software, implementamos diversas programações distintas para os diferentes componentes do projeto, as quais desempenham funções específicas. São elas:

1. Firmware do Relógio:
   - O firmware do relógio é responsável por gerenciar a interface do usuário, processar os dados recebidos e controlar a exibição no display OLED. Ele também gerencia a comunicação com os microcontroladores ESP8266 NodeMCU D1 Mini para coordenação eficaz das funções do dispositivo.

2. Firmware da Caixa de Captação de Som:
   - Esse firmware é desenvolvido para a caixa de captação de som. Ele permite a leitura dos sinais dos microfones posicionados estrategicamente e o envio desses dados para o relógio por meio dos microcontroladores ESP8266 NodeMCU D1 Mini.

3. Firmware para a Integração dos ESP8266 NodeMCU:
   - Esta programação é essencial para a sincronização e comunicação entre os dois microcontroladores ESP8266 NodeMCU D1 Mini, garantindo a eficiência na transmissão e recebimento de dados entre o relógio e a caixa de captação de som.

Cada componente de software desempenha um papel crítico na operação integrada do sistema, garantindo a precisão na detecção de eventos sonoros e a notificação oportuna ao usuário com deficiência auditiva. A sinergia entre essas programações é crucial para o funcionamento eficiente do Projeto .

  
  
## 📫 Diario de Bordo.

 Para obter mais informações detalhadas sobre o progresso da equipe, como por exemplo as reuniões e atividades diárias, até o final do projeto. O recomendado acessar o diário de bordo da equipe 2104, no OneNote, através do link fornecido abaixo.
<p align='center'>
 
  <a href="https://eteacojeorg-my.sharepoint.com/:o:/g/personal/freitas_j_edu_etefmc_com_br/EgUp486kboZGrSqPbz-lGv4BfmcwCqUDRjT4-NkH4WhdEQ?e=SHGIee">
    <img height="120em" src="https://github.com/Jpinguim/Projete-equipe-1102/blob/main/Img/68747470733a2f2f7777772e6132686f73742e636f6d2e62722f626c6f672f77702d636f6e74656e742f75706c6f6164732f323031352f30382f4f6e654e6f74652e706e67.png" />  
  </a>&nbsp;&nbsp;
</p>

## 🕶️ Contribuintes.

 Agradecemos às seguintes pessoas que contribuíram para este projeto:

<table>
  <tr>
     <td align="center">
      <a href="https://instagram.com/pinguinzx">
        <img src="https://github.com/aldinho433/AWP_Projete2104/blob/main/aldo.jpeg" width="100px;" alt="Foto do Pinguim no GitHub"/><br>
        <sub>
          <b><p>Aldo</p><p>Hardware/GitHub</p></b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://instagram.com/pinguinzx">
        <img src="https://github.com/aldinho433/AWP_Projete2104/blob/main/luis.jpeg" width="100px;" alt="Foto do Pinguim no GitHub"/><br>
        <sub>
          <b><p>Eduardo</p><p>Hardware</p></b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="https://www.instagram.com/aldinho.g/">
       <img src="https://github.com/aldinho433/AWP_Projete2104/blob/main/duarte.jpeg" width="130px height="120px";" alt="Foto do Pinguim no GitHub"/><br>
        <sub>
         <b><p>Aldo Gabriel</p><p>Softwar/Diário de bordo</p></b>
        </sub>
      </a>
    </td>
  </tr>
</table>
<table>
  <tr>
    <td align="center">
      <a href="https://instagram.com/arthur_lgc">
       <img src="https://github.com/aldinho433/AWP_Projete2104/blob/main/duardo.jpeg" width="100px;" alt="Foto do Pinguim no GitHub"/><br>
        <sub>
          <b><p>Arthur Brentegani</p><p>Software
</p></b>
        </sub>
      </a>
    </td>
</table>
