import discord
import os

class MyClient(discord.Client):
    async def on_ready(self):
        print('Logged on as {0}!'.format(self.user))

    async def on_message(self, message):
        print('Message from {0.author}: {0.content}'.format(message))
        if message.content == '?regras':
            await message.channel.send(f'{message.author.name} por favor, leia atentamente as regras listadas abaixo:{os.linesep} {os.linesep}O KAUÃ PODE QUEBRAR ESSAS REGRAS SEM RISCO DE BANIMENTO{os.linesep} {os.linesep}1 • Seja educado(a), respeito é bom e de graça, use e abuse dele!{os.linesep}2 • O servidor do discord tem disponibilidade para qualquer pessoa, indiferentemente da etnia, sexualidade, etc.{os.linesep}3 • A utilização do chat de dúvidas deverá ser apenas e unicamente para sanar dúvidas.{os.linesep}4 • A utilização do batepapo deverá ser apenas e unicamente para conversas entre jogadores.{os.linesep}5 • É proibido ofender qualquer jogador ou administrador no discord.{os.linesep}6 • Assédio é estritamente proibido.{os.linesep}7 • Proibido fazer postagens racistas, homofóbicas e com qualquer conteúdo +18.{os.linesep}8 • Recrutamentos devem ser divulgados SOMENTE nas salas especificas.{os.linesep}9 • Evite spam! Mensagens repetidas atrapalham o chat, por favor, tenha bom senso!{os.linesep}10 • Por favor, não grite. Evite o uso excessivo do CAPS LOCK.{os.linesep}11 • Links externos não são permitidos, se necessário a postagem de algum link, encaminhar por pv para um moderador.{os.linesep}12 • É Extremamente Proibido QualQuer Compartilhamento De PornoGrafia, seja Imagem , Foto, Vídeo, Link, Etc...{os.linesep}13 • É proibido a divulgação de outro Discord ou Servidor, caso alguém fique enviando spam sobre outro servidor/discord em seu privado por favor entre em contato com algum ADM/MOD o mais rapido possivel, você será recompensando.{os.linesep} {os.linesep}Informações Adicionais:{os.linesep}* A quebra de uma ou várias regras acima citadas poderá implicar em uma punição.{os.linesep}* As regras podem ser alteradas a qualquer momento, é importante estar sempre atento a qualquer atualização.{os.linesep}* Qualquer duvida ou recomendação de uma possivel nova regra, procure um Administrador.{os.linesep}* As regras não se aplicam a equipe administrativa.{os.linesep} {os.linesep}Sinta-se a vontade para conversar e interagir, aproveite, faça amizades, jogue e divirta-se!')
        elif message.content == '?elogio':
            await message.author.send(f'{message.author.name} você está lindo(a) hoje! s2 s2 s2 s2')
        elif message.content == '?help':
            await message.author.send(f'{message.author.name} esses são os comandos existentes:{os.linesep} {os.linesep}• ?help - Mostra os comandos disponíveis{os.linesep}• ?regras - Mostra as regras do servidor{os.linesep}• ?nivel - Mostra o seu nivel no servidor{os.linesep}• ?elogio - Manda um elogio para você na dm')

client = MyClient()
client.run('Coloque sua Key')
