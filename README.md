# Zkopírovat na server a nastavit oprávnění
chmod +x starcore-auto-builder-v3.0.sh

# Běžný spuštění (jako root, protože píše do /root/starcore)
./starcore-auto-builder-v3.0.sh

# S automatickou instalací chybějících nástrojů (python3, node, tput...)
AUTO_INSTALL_MISSING=1 ./starcore-auto-builder-v3.0.sh

# Zastavení: Ctrl+C — stav se uloží, příští spuštění naváže (resume)
