# Roteiro Oratória de Mestre

Skill para o Codex que cria um **roteiro falado original** usando a arquitetura narrativa da aula [“Oratória de MESTRE”, de Fe Alves](https://www.youtube.com/watch?v=8DnfIrNF2HU).

Ela usa a sequência da aula como molde: promessa e custo do problema, história e autoridade, mudança de perspectiva, fundamentos com demonstrações, aplicação, obstáculo, treino e fechamento. O tema, os exemplos, as histórias e as falas do novo vídeo são próprios de quem vai gravá-lo.

## Instalação no Codex

Clone este repositório e copie a skill para a pasta de skills:

```bash
git clone https://github.com/saraivabr/roteiro-oratoria-de-mestre.git
mkdir -p ~/.codex/skills/roteiro-oratoria-de-mestre
cp roteiro-oratoria-de-mestre/SKILL.md ~/.codex/skills/roteiro-oratoria-de-mestre/
cp -R roteiro-oratoria-de-mestre/references ~/.codex/skills/roteiro-oratoria-de-mestre/
```

## Como usar

No Codex, peça por exemplo:

> Use `$roteiro-oratoria-de-mestre` para criar uma masterclass de 45 minutos sobre como pequenas empresas podem usar IA no atendimento. O público são donos de negócio que já recebem mensagens no WhatsApp. Quero um roteiro completo para falar à câmera, com exemplos e indicações de pausa.

Informe pelo menos o **tema**. Público, objetivo e duração ajudam a calibrar o texto. A skill gera o roteiro integral com blocos e tempos estimados, demonstrações faladas e uma ficha curta de gravação. Se você pedir apenas um esqueleto ou trecho piloto, ela limita a entrega a esse escopo.

## Arquivos

- [`SKILL.md`](SKILL.md): instruções de geração do roteiro.
- [`references/estrutura.md`](references/estrutura.md): mapa dos capítulos e da função narrativa do vídeo de referência.

A análise estrutural se baseou na transcrição automática e na inspeção visual de trechos do vídeo. Ela não inclui transcrição integral nem material audiovisual do criador. Esta skill é independente e não tem associação com Fe Alves.
