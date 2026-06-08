# FinBot
Desafio Projeto Assistente Virtual Com Inteligência Artificial.

# Base de Conhecimento - FinBot (Assistente de Finanças Pessoais)

## ORÇAMENTO E CONTROLE FINANCEIRO

**O que é orçamento pessoal?**
Orçamento pessoal é o planejamento de quanto você ganha e quanto gasta em um período. É a base de qualquer saúde financeira.

**Regra 50-30-20:**
Uma forma simples de dividir sua renda:
- 50% para necessidades (aluguel, comida, transporte, contas fixas)
- 30% para desejos (lazer, restaurantes, streaming, roupas)
- 20% para poupança e investimentos

**Como montar um orçamento simples:**
1. Some toda a sua renda mensal
2. Liste todos os seus gastos fixos
3. Liste os gastos variáveis dos últimos 3 meses
4. Calcule a média mensal de cada categoria
5. Veja onde está sobrando ou faltando

---

## DÍVIDAS E COMO SAIR DELAS

**Tipos comuns de dívidas:**
- Cartão de crédito: juros altíssimos (até 400% ao ano), prioridade máxima para quitar
- Cheque especial: também tem juros muito altos, evitar usar
- Crédito consignado: juros mais baixos, geralmente descontado em folha
- Financiamento de carro/imóvel: juros médios, parcelas fixas

**Método Avalanche (mais econômico):**
Pague o mínimo de todas as dívidas e coloque o dinheiro extra na de maior juros primeiro.

**Método Bola de Neve (mais motivador):**
Pague o mínimo de todas e coloque o extra na dívida de menor valor primeiro. Quando quitar, use esse dinheiro na próxima.

**O que fazer se não conseguir pagar:**
- Negocie diretamente com o credor antes de atrasar
- Procure o Serasa Limpa Nome ou a plataforma do banco
- Evite pegar empréstimo para pagar dívida, a menos que os juros sejam bem menores

---

## RESERVA DE EMERGÊNCIA

**O que é?**
Dinheiro guardado para imprevistos: perda de emprego, problemas de saúde, consertos urgentes.

**Quanto guardar?**
- Mínimo: 3 meses dos seus gastos mensais
- Ideal: 6 meses
- Profissionais autônomos: até 12 meses (renda instável)

**Onde guardar?**
- Conta poupança: segura, mas rendimento baixo
- Tesouro Selic: rende mais que poupança, seguro, fácil de resgatar
- CDB com liquidez diária: boa opção em bancos digitais

**Regra importante:** Reserva de emergência não é investimento. É proteção. Não misture com objetivos de médio prazo.

---

## INVESTIMENTOS PARA INICIANTES

**Antes de investir, garanta:**
1. Reserva de emergência formada
2. Dívidas caras quitadas (cartão, cheque especial)

**Tipos de investimento por perfil:**

*Conservador (quer segurança):*
- Tesouro Direto (Tesouro Selic ou IPCA+)
- CDB de bancos sólidos
- LCI e LCA (isentos de IR para pessoa física)

*Moderado (aceita algum risco):*
- Fundos de investimento multimercado
- Debêntures
- Fundos imobiliários (FIIs)

*Arrojado (aceita risco maior):*
- Ações na bolsa de valores
- ETFs (fundos que seguem índices como o Ibovespa)
- Criptomoedas (alto risco, use só o que pode perder)

**Regra de ouro:** Nunca invista em algo que não entende. Comece simples.

---

## CARTÃO DE CRÉDITO

**Como usar de forma saudável:**
- Pague sempre o valor total da fatura, nunca o mínimo
- Use como ferramenta de organização, não como extensão de renda
- Prefira cartões sem anuidade se você gasta pouco
- Cuidado com parcelamentos: eles comprometem renda futura

**Situações de alerta:**
- Usar cartão para pagar contas básicas (luz, aluguel) sem conseguir pagar a fatura
- Pagar apenas o mínimo todo mês
- Não saber quanto está gastando no cartão

---

## METAS FINANCEIRAS

**Como definir uma meta financeira:**
- Seja específico: "Quero guardar R$5.000 para viagem em 12 meses"
- Calcule quanto precisa guardar por mês: R$5.000 ÷ 12 = R$417/mês
- Revise o orçamento para encaixar esse valor

**Exemplos de metas comuns:**
- Reserva de emergência
- Entrada para imóvel
- Troca de carro
- Viagem
- Aposentadoria
- Curso ou faculdade

---

## PERGUNTAS FREQUENTES

**Quanto devo guardar por mês?**
O ideal é pelo menos 10% da renda. Se não conseguir, comece com o que puder: R$50, R$100. O hábito é mais importante que o valor inicial.

**Vale a pena investir com pouco dinheiro?**
Sim. O Tesouro Direto aceita aplicações a partir de R$30. O importante é começar.

**Devo quitar dívida ou investir?**
Se a dívida tem juros maiores do que o rendimento do investimento (quase sempre é o caso com cartão e cheque especial), quite a dívida primeiro.

**Como sair do vermelho?**
1. Pare de criar novas dívidas
2. Liste tudo que deve
3. Negocie os juros
4. Corte gastos não essenciais
5. Siga um método de pagamento (avalanche ou bola de neve)

"""
# Documentação do Agente - FinBot

## 1. O que é o FinBot?

O **FinBot** é um assistente virtual de finanças pessoais criado para ajudar pessoas comuns — especialmente iniciantes — a tomar decisões financeiras mais conscientes no dia a dia.

Ele não substitui um planejador financeiro profissional, mas serve como um primeiro passo acessível para quem quer organizar a vida financeira sem precisar pagar por uma consultoria.

---

## 2. Para quem serve?

**Público-alvo principal:**
- Pessoas que estão começando a se preocupar com finanças
- Quem está endividado e não sabe por onde começar
- Quem quer começar a investir, mas tem medo ou dúvidas
- Quem quer organizar o orçamento mensal

**Perfil da persona:**
> "Ana tem 28 anos, trabalha com carteira assinada, gasta mais do que ganha no cartão de crédito e quer mudar esse cenário, mas não sabe por onde começar."

---

## 3. Objetivo do Assistente

O FinBot deve ser capaz de:
- Explicar conceitos financeiros de forma simples
- Ajudar o usuário a entender sua situação atual
- Sugerir próximos passos práticos
- Responder dúvidas com base em uma base de conhecimento organizada
- Admitir quando não sabe ou quando o usuário precisa de ajuda profissional

---

## 4. Tom e Comportamento

| Característica | Descrição |
|---|---|
| Tom | Amigável, direto, sem jargões desnecessários |
| Postura | Paciente, sem julgamentos sobre situação financeira |
| Limites | Não inventa dados, não garante rendimentos, não dá conselho de investimento específico |
| Transparência | Informa quando a pergunta está fora do seu escopo |

---

## 5. O que o FinBot NÃO faz

- Não acessa dados bancários reais
- Não garante resultados financeiros
- Não substitui consultoria jurídica ou contábil
- Não recomenda produtos financeiros específicos (ex: "compre ação X")
- Não inventa informações quando não sabe a resposta

---

## 6. Fluxo básico de conversa

```
Usuário inicia conversa
       ↓
FinBot se apresenta e pergunta como pode ajudar
       ↓
Usuário descreve situação ou dúvida
       ↓
FinBot busca na base de conhecimento
       ↓
FinBot responde de forma clara e sugere próximo passo
       ↓
Usuário pode continuar ou encerrar
```
###################################################################
"""
**FinBot - Assistente Virtual de Finanças Pessoais**
Projeto desenvolvido para o Lab da DIO: Construa Seu Assistente Virtual Com IA
"""

import anthropic
import os

<img width="1290" height="500" alt="image" src="https://github.com/user-attachments/assets/c5f4444a-ef0d-4f18-a109-24d534167595" />



https://github.com/user-attachments/assets/e73b3c58-c16d-4941-afee-e2fd181ec24a


# 
# 1. CARREGA A BASE DE CONHECIMENTO
# 

def carregar_base_de_conhecimento(caminho: str) -> str:
    """Lê o arquivo de texto com a base de conhecimento."""
    try:
        with open(caminho, "r", encoding="utf-8") as arquivo:
            return arquivo.read()
    except FileNotFoundError:
        print(f"[ERRO] Arquivo '{caminho}' não encontrado.")
        return ""


#
# 2. MONTA O PROMPT DO SISTEMA
# 

def criar_system_prompt(base_de_conhecimento: str) -> str:
    """Injeta a base de conhecimento no prompt do sistema."""
    return f"""Você é o FinBot, um assistente virtual de finanças pessoais criado para ajudar pessoas comuns a organizarem sua vida financeira.

Seu papel é:
- Responder dúvidas sobre orçamento, dívidas, reserva de emergência e investimentos iniciantes
- Usar linguagem simples, sem jargões técnicos desnecessários
- Ser empático e não julgar a situação financeira do usuário
- Sempre sugerir um próximo passo prático ao final de cada resposta
- Basear suas respostas na base de conhecimento fornecida abaixo

Regras importantes:
- Se a pergunta estiver fora do escopo financeiro, diga educadamente que só pode ajudar com finanças pessoais
- Se não souber a resposta, diga "Não tenho informação suficiente sobre isso. Recomendo consultar um profissional financeiro."
- Nunca invente dados, taxas ou rendimentos específicos
- Nunca recomende produtos financeiros específicos pelo nome
- Se o usuário parecer em crise financeira grave, sugira buscar ajuda no Procon ou Serasa Limpa Nome

BASE DE CONHECIMENTO:
{base_de_conhecimento}"""


# 
# 3. FUNÇÃO PRINCIPAL DE CHAT
#

def chat_com_finbot():
    """Loop principal de conversa com o FinBot."""

    # Inicializa o cliente da API Anthropic
    # A chave é lida automaticamente da variável de ambiente ANTHROPIC_API_KEY
    cliente = anthropic.Anthropic()

    # Carrega a base de conhecimento
    base = carregar_base_de_conhecimento("data/conhecimento.txt")
    system_prompt = criar_system_prompt(base)

    # Histórico da conversa (mantém contexto entre mensagens)
    historico = []

    # Cabeçalho do assistente
    print("\n" + "="*50)
    print("  💰 FinBot - Assistente de Finanças Pessoais")
    print("="*50)
    print("\nOlá! Eu sou o FinBot 💰, seu assistente de finanças pessoais.")
    print("\nPosso te ajudar com:")
    print("  • Montar um orçamento")
    print("  • Sair das dívidas")
    print("  • Construir sua reserva de emergência")
    print("  • Dar os primeiros passos em investimentos")
    print("\nDigite 'sair' a qualquer momento para encerrar.")
    print("-"*50)

    # Loop da conversa
    while True:
        # Lê a mensagem do usuário
        print()
        usuario_input = input("Você: ").strip()

        # Condição de saída
        if usuario_input.lower() in ["sair", "exit", "quit"]:
            print("\nFinBot: Até logo! Bons estudos financeiros 🚀\n")
            break

        # Ignora entradas vazias
        if not usuario_input:
            continue

        # Adiciona a mensagem do usuário ao histórico
        historico.append({
            "role": "user",
            "content": usuario_input
        })

        # Chama a API do Claude
        try:
            resposta = cliente.messages.create(
                model="claude-sonnet-4-20250514",
                max_tokens=1024,
                system=system_prompt,
                messages=historico
            )

            # Extrai o texto da resposta
            texto_resposta = resposta.content[0].text

            # Adiciona a resposta ao histórico (mantém contexto)
            historico.append({
                "role": "assistant",
                "content": texto_resposta
            })

            # Exibe a resposta
            print(f"\nFinBot: {texto_resposta}")
            print("-"*50)

        except anthropic.APIConnectionError:
            print("\n[ERRO] Não foi possível conectar à API. Verifique sua internet.")
        except anthropic.AuthenticationError:
            print("\n[ERRO] Chave de API inválida. Verifique a variável ANTHROPIC_API_KEY.")
        except Exception as erro:
            print(f"\n[ERRO] Algo deu errado: {erro}")


# 
# 4. PONTO DE ENTRADA
#

if __name__ == "__main__":
    chat_com_finbot()
      

