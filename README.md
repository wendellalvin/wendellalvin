-from art import text2art

# Função para criar um banner de texto
def create_banner(text):
    banner = text2art(text, font='block')  # Você pode escolher outras fontes disponíveis
    return banner

# Informações do anúncio
job_title = "Oportunidade de Trabalho: Secretário Executivo na Good Trip"
requirements = "- Curso superior em Secretariado Executivo ou Comunicação.\n- Experiência comprovada na função.\n- Organização e habilidades de comunicação excepcionais.\n- Excelente redação e bom relacionamento interpessoal.\n- Domínio das ferramentas do pacote Office.\n- Nível avançado de inglês."
benefits = "- Salário: R$ 5.000,00.\n- Assistência médica e odontológica.\n- Vale-refeição.\n- Bolsa auxílio educação.\n- Plano de previdência privada."
working_hours = "Horário de trabalho: Segunda a sexta-feira, das 8h às 17h."

# Criar o banner
banner_text = f"{job_title}\n\n{requirements}\n\n{benefits}\n\n{working_hours}"
banner = create_banner(banner_text)

# Exibir o banner
print(banner)

