# GitHub Copilot Login - 10 IDEs JetBrains

## Pré-requisitos
- GitHub Copilot ativo (Individual, Business ou Enterprise)
- Educational Pack BD24G146N7 válido até 2027-08-23
- Todas as 10 IDEs instaladas via snap (2026.2.x)

## Passo a Passo por IDE

### 1. CLion
```
1. Abra CLion
2. Ctrl+Shift+A → "GitHub Copilot: Sign In"
3. Copie o código exibido (ex: ABCD-1234)
4. Abra https://github.com/login/device no navegador
5. Cole o código e autorize
6. Volte ao CLion - status "Signed in" aparece no canto inferior direito
```

### 2. DataGrip
```
1. Abra DataGrip
2. Ctrl+Shift+A → "GitHub Copilot: Sign In"
3. Mesmo fluxo device code
```

### 3. GoLand
```
1. Abra GoLand
2. Ctrl+Shift+A → "GitHub Copilot: Sign In"
3. Mesmo fluxo device code
```

### 4. IntelliJ Ultimate
```
1. Abra IntelliJ Ultimate
2. Ctrl+Shift+A → "GitHub Copilot: Sign In"
3. Mesmo fluxo device code
```

### 5. PhpStorm
```
1. Abra PhpStorm
2. Ctrl+Shift+A → "GitHub Copilot: Sign In"
3. Mesmo fluxo device code
```

### 6. PyCharm Professional
```
1. Abra PyCharm Pro
2. Ctrl+Shift+A → "GitHub Copilot: Sign In"
3. Mesmo fluxo device code
```

### 7. Rider
```
1. Abra Rider
2. Ctrl+Shift+A → "GitHub Copilot: Sign In"
3. Mesmo fluxo device code
```

### 8. RubyMine
```
1. Abra RubyMine
2. Ctrl+Shift+A → "GitHub Copilot: Sign In"
3. Mesmo fluxo device code
```

### 9. RustRover
```
1. Abra RustRover
2. Ctrl+Shift+A → "GitHub Copilot: Sign In"
3. Mesmo fluxo device code
```

### 10. WebStorm
```
1. Abra WebStorm
2. Ctrl+Shift+A → "GitHub Copilot: Sign In"
3. Mesmo fluxo device code
```

## Verificação em Massa

### Via Terminal (verificar plugin instalado)
```bash
# Verificar se plugin Copilot está instalado em cada IDE
for ide in clion datagrip goland idea phpstorm pycharm rider rubymine rustrover webstorm; do
  echo "=== $ide ==="
  find ~/snap/$ide/current -name "*copilot*" 2>/dev/null | head -5
done
```

### Atalho Universal
Todas as IDEs JetBrains 2026.2+:
- **Ctrl+Shift+A** → digite "GitHub Copilot" → Enter
- Ou: **View → Tool Windows → GitHub Copilot**

## Configurações Recomendadas

### Settings → Tools → GitHub Copilot
- ✅ Enable Copilot
- ✅ Show suggestions automatically
- ✅ Enable in comments
- Suggestion delay: 100ms
- Max suggestions: 10

### Keyboard Shortcuts (personalizar em Keymap)
| Ação | Atalho Sugerido |
|------|----------------|
| Accept suggestion | Tab |
| Dismiss suggestion | Esc |
| Next suggestion | Alt+] |
| Previous suggestion | Alt+[ |
| Open Copilot Chat | Ctrl+Shift+C |
| Explain code | Ctrl+Shift+E |
| Generate tests | Ctrl+Shift+T |

## Troubleshooting

### "Plugin not found"
```bash
# Reinstalar plugin via marketplace
# Settings → Plugins → Marketplace → "GitHub Copilot" → Install → Restart IDE
```

### "Authentication failed"
1. Revogar acesso em: GitHub Settings → Applications → Authorized OAuth Apps → GitHub Copilot
2. Refazer login na IDE

### "Educational license not recognized"
- Verificar se conta GitHub tem Educational Pack ativo
- Settings → Appearance → Licenses → Verify Educational License

## Automação (Opcional)

### Script para abrir todas as IDEs sequencialmente
```bash
#!/bin/bash
ides=(clion datagrip goland idea phpstorm pycharm rider rubymine rustrover webstorm)
for ide in "${ides[@]}"; do
  echo "Abrindo $ide para login Copilot..."
  $ide &
  sleep 3
done
echo "Faça login em cada janela (Ctrl+Shift+A → GitHub Copilot: Sign In)"
```

## Links Úteis
- [Copilot Docs](https://docs.github.com/en/copilot)
- [JetBrains Copilot Plugin](https://plugins.jetbrains.com/plugin/19613-github-copilot)
- [Device Code Flow](https://github.com/login/device)

---

**Nota**: O login precisa ser feito manualmente em cada IDE. Não há automação completa via CLI devido ao fluxo OAuth device code.
