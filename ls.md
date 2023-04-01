# Comando ls

Comando ls serve para demostrar o que está em uma pasa/diretório, ls vem de "list directory".

---

## Exemplo 1

Entrada:
```bash
ls
```

Saida:
```
pasta1  teste.txt
```

---

### Opções:

```
-a, --all  -> Mostrar as diretórios ou arquivos ocultos
-l         -> Lista longa
-h         -> Para humano lerem, para ficar mais simples de ler
```

---

## Exemplo 2

Entrada:

```bash
ls -lha
```

Saida:

```
total 16K
drwxr-xr-x 3 lucas lucas 4,0K mar 31 22:28 .
drwxr-xr-x 4 lucas lucas 4,0K mar 31 22:26 ..
drwxr-xr-x 3 lucas lucas 4,0K mar 31 22:27 pasta1
-rw-r--r-- 1 lucas lucas   21 mar 31 22:28 teste.txt
```
