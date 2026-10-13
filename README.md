# Rodízio Barca

Aplicação Android para gerir o rodízio dos cultos: quem faz em cada dia, a Santa Ceia, os ensaios e os hinos a ensaiar, com PDF mensal, mensagem para o grupo, notificações e widgets.

Este repositório serve apenas para distribuir a aplicação (ficheiro APK). O código-fonte é privado.

## ⬇️ Descarregar

**[Descarregar a versão mais recente](https://github.com/Larklius/rodizio-releases/releases/latest)**. Na página que abre, em **Assets**, toca em `Rodizio-Barca-vX.Y.Z.apk`.

Requisitos: telemóvel Android 7.0 ou superior.

## 📲 Instalar pela primeira vez

1. **Descarregar**: no telemóvel, abre o link acima no browser (por exemplo o Chrome) e toca no ficheiro `.apk`.
   Se o Chrome avisar que *"este tipo de ficheiro pode ser prejudicial"*, toca em **Transferir mesmo assim**.
2. **Abrir o ficheiro**: quando a transferência terminar, toca em **Abrir** na notificação, ou vai a *Ficheiros → Transferências*.
3. **Permitir a instalação**: na primeira vez o Android mostra *"Por segurança, o telemóvel não pode instalar apps desta origem"*.
   Toca em **Definições**, ativa **Permitir desta origem** para o Chrome (ou para a app Ficheiros) e volta atrás.
4. **Instalar**: toca em **Instalar**.

### Avisos que podem aparecer

| Aviso | O que fazer |
|---|---|
| **Google Play Protect**: "App não verificada" / "App desconhecida" | Toca em **Mais detalhes → Instalar mesmo assim**. A app não está na Play Store, por isso o aviso é normal. |
| "Enviar a app para análise?" | Podes recusar. |
| "**App não instalada**" / "o pacote está em conflito" | Já tens uma versão assinada com outra chave. Faz um backup nas Configurações da app, desinstala-a e instala de novo. |

## 🔄 Atualizar

Depois da primeira instalação não precisas de voltar aqui:

1. Na app, toca em ⚙️ e abre **Atualizações → Verificar atualizações**.
2. Toca em **Instalar**. A app descarrega e abre o instalador.
3. Na primeira vez, o Android pede **Permitir desta origem** para a própria app (Rodízio Barca). Ativa e volta atrás.

Os teus dados **mantêm-se** ao atualizar.

## ⚙️ Depois de instalar (opcional)

- **Notificações**: em ⚙️ → **Notificações**, ativa-as para receberes o aviso de quem faz em cada dia e dos ensaios. Em alguns telemóveis (Xiaomi, Oppo, Realme) é preciso tirar a app da poupança de bateria: *Definições → Apps → Rodízio Barca → Bateria → Sem restrições*.
- **Widgets**: mantém premido o ecrã inicial, escolhe **Widgets → Rodízio Barca** e arrasta o widget que quiseres (o rodízio ou o ensaio e os hinos).
- **Programa antigo**: em ⚙️ → **Dados e backup → Importar backup** podes carregar o ficheiro `rodizio_config.json` do programa do computador.

## 🔒 Privacidade

Os dados ficam apenas no telemóvel. Não há contas nem servidores. A app guarda uma cópia de segurança por semana na pasta *Documentos/RodizioBarca* do telemóvel; copia esse ficheiro para outro sítio de vez em quando, para não perderes os dados se trocares de telemóvel.
