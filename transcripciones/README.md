# Transcripciones de audios

Transcripción automática en español de 11 grabaciones (≈58 min). Los audios originales están en la raíz de la rama `main`.

## Contenido

- `txt/`: texto plano, una línea por segmento.
- `srt/`: subtítulos con marcas de tiempo.

| Transcripción | Audio original | Duración | Palabras |
|---|---|---|---|
| [AUD-20261106-WA0002.txt](txt/AUD-20261106-WA0002.txt) · [srt](srt/AUD-20261106-WA0002.srt) | `AUD-20261106-WA0002.mp3` | 9:51 | 1321 |
| [AUD-20261107-WA0004.txt](txt/AUD-20261107-WA0004.txt) · [srt](srt/AUD-20261107-WA0004.srt) | `AUD-20261107-WA0004.m4a` | 3:30 | 578 |
| [AUD-20261107-WA0005.txt](txt/AUD-20261107-WA0005.txt) · [srt](srt/AUD-20261107-WA0005.srt) | `AUD-20261107-WA0005.m4a` | 1:31 | 238 |
| [AUD-20261107-WA0006.txt](txt/AUD-20261107-WA0006.txt) · [srt](srt/AUD-20261107-WA0006.srt) | `AUD-20261107-WA0006.aac` | 4:53 | 290 |
| [AUD-20261107-WA0007.txt](txt/AUD-20261107-WA0007.txt) · [srt](srt/AUD-20261107-WA0007.srt) | `AUD-20261107-WA0007.m4a` | 2:13 | 176 |
| [AUD-20261107-WA0008.txt](txt/AUD-20261107-WA0008.txt) · [srt](srt/AUD-20261107-WA0008.srt) | `AUD-20261107-WA0008.m4a` | 7:03 | 1103 |
| [AUD-20261107-WA0009.txt](txt/AUD-20261107-WA0009.txt) · [srt](srt/AUD-20261107-WA0009.srt) | `AUD-20261107-WA0009.m4a` | 9:14 | 1351 |
| [Cementos.txt](txt/Cementos.txt) · [srt](srt/Cementos.srt) | `Cementos.m4a` | 12:27 | 958 |
| [Centro Hierros.txt](txt/Centro%20Hierros.txt) · [srt](srt/Centro%20Hierros.srt) | `Centro Hierros.m4a` | 4:42 | 635 |
| [Tec.txt](txt/Tec.txt) · [srt](srt/Tec.srt) | `Tec.m4a` | 2:20 | 312 |
| [Voice 011.txt](txt/Voice%20011.txt) · [srt](srt/Voice%20011.srt) | `Voice 011.m4a` | 0:47 | 38 |

## Cómo se generaron

- Herramienta: [babelscribe](https://github.com/phonology024/babelscribe) 0.4.0 (whisper.cpp), modelo `large-v3-turbo`, idioma `es`, ejecutado en CPU.
- Comando por archivo: `uvx babelscribe <audio> -l es -f txt,srt`

## Limitaciones

- **No han sido revisadas manualmente.** Whisper puede errar en nombres propios, empresas y términos técnicos.
- `AUD-20261107-WA0006` tiene pocas palabras para su duración (silencios largos o audio de baja calidad).
- `AUD-20261106-WA0002` contiene contenido que no parece una entrevista de mercado; conviene verificar que pertenece a la serie.
