# Labtainer Guide

## Install
1. Descărcați arhiva de pe [Labtainers Website](https://nps.edu/web/c3o/labtainers).
2. Extrageți arhiva:
   ```bash
   tar xvf labtainer.tar
   ```
3. Navigați în directorul `labtainer`:
   ```bash
   cd labtainer
   ```
4. Rulați scriptul de instalare:
   ```bash
   ./install-labtainer.sh
   ```
   Acest script va instala toate dependențele necesare și va efectua un restart al sistemului.

## Selectarea laboratorului
Pentru a vedea toate laboratoarele disponibile, introduceți:
```bash
labtainer
```
- Folosiți `-f` pentru a căuta un laborator după numele său.

## Aranjarea după funcționalitate
Pentru a vedea un meniu de ajutor cu pachetele disponibile:
```bash
labpack
```
Exemplu pentru a vizualiza laboratoarele dintr-un modul specific:
```bash
labpack acess
```
Aici veți vedea toate laboratoarele disponibile pentru modulul selectat.

## Rularea unui laborator
Pentru a porni un laborator, introduceți:
```bash
labtainer <labname>
```

## Stoparea laboratorului
Pentru a opri un laborator:
```bash
stoplab
```

## Refacerea laboratorului
Pentru a reseta un laborator:
```bash
labtainer -r <labname>
```

## Verificarea laboratorului
Pentru a verifica dacă ați rezolvat corect un laborator:
```bash
checkwork telnetlab
```


## Network-intro
| Name | Write-UP                                                               | Status  |
|------------|--------------------------------------------------------------------|---------|
| network-basics   | [ret2win](https://ropemporium.com/challenge/ret2win.html)          | ✅       |
| Test    | [ret2csu](https://ropemporium.com/challenge/ret2csu.html)          | ❌       |
