# Sonic Pi

"Sonic Pi is a code-based music creation and performance tool."

---

### Exemplos a serem trabalhados

```
play 60
```

```
play 60
sleep
play 72
```

```
play 30, amp: 5
```

```
play 60
play 75 + 4
```
```
use_synth :prophet
play :e1, release: 8
```
```
use_synth :prophet
play :e1, release: 8, cutoff: 110
```

```
use_synth :prophet
play :e1 + 8 + 12, release: 8, cutoff: 110
```

```
sample :ambi_lunar_land, amp: 10, rate: 1.5
```

```
loop do
    synth :tb303, note: :e1, release: 0.3
    sleep 0.5
end
```

```
8.times do
  play (scale :e4, :minor_pentatonic).choose, release: 0.1
  sleep 1
end
```
---
### Procurando exemplos no Sonic Pi

Help / Exemplos

---

### Tabela de notas MIDI

![](/images/midi-int-midi-note-no-chart.jpg)

---
### Referências:


Mello, Patricia Oakim Bandeira de. Arte e programação na linguagem Processing. 2015. 137 f. Dissertação (Mestrado em Mídias Digitais) - Pontifícia Universidade Católica de São Paulo, São Paulo, 2015. Disponível em: <https://tede2.pucsp.br/handle/handle/18199/>. Acesso em: 11 de julho de 2020.


Sites:

OPENPROCESSING. Disponível em <https://www.openprocessing.org/>. Acesso em: 11 de julho de 2020.

SONIC PI. Disponível em <https://sonic-pi.net/>. Acesso em: 11 de julho de 2020.

PROCESSING. Disponível em <http://processing.org/>. Acesso em: 11 de julho de 2020.


Videos: 

GOTO 2018 – Get Ready to Rock with Sonic Pi – The Live Coding Music Synth for Everyone – Sam Aaron. Youtube. Disponível em: https://www.youtube.com/watch?v=OLLwG_SN8oo&t=69s>. Acesso em 21 de julho de 2020.

Imagens:

IMAGEM tabela Midi. <http://electronicalacho.blogspot.com/2013/07/crea-tu-propio-controlador-midi-desde-0_23.html>

