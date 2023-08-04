# TERMINATOR CONFIG

Configuração otimizada para o emulador de terminal Terminator.

## Global Config

**[global_config]**: Este bloco define as configurações globais para o Terminator.
- **enabled_plugins**: Lista os plugins que você deseja ativar no Terminator. Neste caso, os plugins como TerminalShot (captura de tela do terminal) e vários outros relacionados ao Launchpad e APT estão ativados.

## Keybindings

**[keybindings]**: Este bloco seria usado para definir atalhos personalizados para diferentes funções no Terminator. No entanto, neste caso, está vazio, o que significa que você está usando os atalhos padrão.

## Profiles

**[profiles]**: Define os perfis de configuração para seus terminais. Um perfil contém um conjunto de configurações que determinam a aparência e o comportamento do terminal.

### Default

- **background_darkness**: Define a opacidade do fundo (0.0 é totalmente transparente, 1.0 é totalmente opaco).
- **background_type**: Define o tipo de fundo, neste caso, transparente.
- **font**: Define a fonte e o tamanho utilizados no terminal.
- **show_titlebar**: Se falso, oculta a barra de título do terminal.
- **scrollbar_position**: Define a posição da barra de rolagem, que está oculta aqui.
- **scroll_on_keystroke**: Se falso, o terminal não rola automaticamente ao digitar.
- **scrollback_infinite**: Se verdadeiro, o buffer de rolagem permite rolagem infinita.
- **palette**: Define a paleta de cores personalizada para o terminal.
- **use_system_font**: Se falso, o terminal usará a fonte especificada em vez da fonte do sistema.
- **use_theme_colors**: Se verdadeiro, utiliza as cores do tema do sistema.
- **custom_command**: Comando personalizado para ser executado quando o terminal é iniciado.
- **use_custom_command**: Se verdadeiro, executa o comando personalizado especificado.

## Layouts

**[layouts]**: Define os layouts para as janelas e terminais. Pode ser útil se você quiser iniciar o Terminator com um layout específico de janelas e abas.

### Default

- **[[[window0]]]**: Define as propriedades para a primeira janela.
  - **type**: Especifica o tipo de widget, que é uma janela neste caso.
  - **parent**: Para elementos de layout hierárquicos, isto define o elemento pai. Está vazio aqui porque é a janela principal.
  - **size**: Define o tamanho da janela.
- **[[[child1]]]**: Define as propriedades para o primeiro terminal.
  - **type**: Especifica o tipo de widget, que é um terminal neste caso.
  - **parent**: Define a janela pai para este terminal.
  - **profile**: Especifica o perfil a ser usado por este terminal.

## Plugins

**[plugins]**: Este bloco seria usado para definir configurações para os plugins ativados no Terminator. No entanto, está vazio neste caso, o que significa que você está usando as configurações padrão para os plugins ativados.
