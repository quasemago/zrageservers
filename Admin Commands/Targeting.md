# Modos de target

## Target individual

**Nome do jogador:** <br />
Nome exato do jogador, em caso de nomes que tenham espaço utilizar o nome entre aspas.
> Exemplo 1: sm_kick Dummy <br>
> Exemplo 2: sm_kick "Dummy" <br>
> Exemplo 3: sm_kick "Dummy Teste" (Nomes que possuem espaço todo entre parênteses)

<br />

**User Id:** <br /> 
Após dar status no console você irá ver o nome dos jogadores conectados e verá que há no começo de cada linha o seguinte formato *# 572 1 "Dummy Test" STEAM_0:0:000000 00:00 64 0 active 256000 000.00.000.000:00000*.<br /> <br /> 
Esse jogo da velha + número identificam o jogador localmente no servidor. Esse números mudam no disconnect do jogador. Mas são bons caso o jogador possua um nome ilegivel ou identico a outro jogador
> Exemplo: sm_kick #572 (Irá banir o jogador Dummy Test)

<br />

**Steam Id:**<br />
Inserir a SteamID de um jogador tbm funcionará. Caso queira utilizar com : terá que colocar entre aspas. Se não terá que substituir : por _ .
> Exemplo 1: sm_kick "#STEAM_0:1:4433" <br>
> Exemplo 2: sm_kick #STEAM_0_1_4433

---

## Target em grupos 
##### Obs: *Nem todos os comandos funcionam com grupos de target.*

**@all:** <br />
Target em todos os jogadores do servidor.
> Exemplo: sm_kick @all

<br />

**@ct ou @cts:** <br />
Target em todos os jogadores do time de CT/Humano.
> Exemplo: sm_kick @ct

<br />

**@t ou @ts:** <br />
Target em todos os jogadores do time T/Zumbi.
> Exemplo: sm_kick @t

<br />

**@aim:** <br />
Target no jogador em que sua mira está atingindo (Meio bugado)
> Exemplo: sm_kick @aim

<br />

**@me:** <br />
Target em você mesmo
> Exemplo: sm_kick @me

<br />

**@!me:** <br />
Target em todos menos você
> Exemplo: sm_kick @!me
