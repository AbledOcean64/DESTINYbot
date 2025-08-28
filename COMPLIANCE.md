# Guia de Conformidade e Uso Ético

## ✅ Uso Permitido
- Notificações de reset diário/semanal
- Informações sobre localização do Xur
- Notícias e updates de Destiny 2
- Comandos sob demanda para grupos pequenos

## ❌ Uso Proibido
- Spamming em múltiplos grupos
- Mensagens automáticas em larga escala
- Uso comercial sem autorização
- Coleta de dados pessoais
- Violação de termos de serviço

## Melhores Práticas
1. **Rate Limiting**: Respeite os limites da API Bungie
2. **Cache**: Use cache para evitar requisições desnecessárias
3. **Transparência**: Deixe claro que é um bot para os usuários
4. **Opt-out**: Permita que usuários parem de receber mensagens

## Configuração Recomendada
```python
# config.py
BOT_CONFIG = {
    "behavior": {
        "max_messages_per_hour": 20,
        "min_response_delay": 5,
        "respect_working_hours": True,
    }
}
