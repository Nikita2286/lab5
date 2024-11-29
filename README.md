Sigur! Iată varianta fără secțiunea de rulare:

---

# SnakeGame

**Denumirea proiectului**: SnakeGame

**Descriere**: SnakeGame este o implementare clasică a jocului retro "Snake", în care jucătorul controlează un șarpe care se mișcă pe o tablă de joc și trebuie să mănânce obiecte (mere) care apar aleatoriu. Fiecare obiect mâncat face ca șarpele să crească în lungime, iar jocul devine mai dificil pe măsură ce avansezi. Jocul se încheie atunci când șarpele lovește un perete sau se auto-colizionează.

**Reguli**:
- Controlează un șarpe pe o tablă de joc.
- Mănâncă mere pentru a crește în lungime.
- Evită să lovești pereții sau să te auto-colizionezi.
- Jocul se încheie atunci când șarpele moare.

## Structura proiectului

- **point.hpp / point.cpp**: Gestionarea coordonatelor.
- **board.hpp / board.cpp**: Dimensiunile tablei de joc.
- **snake.hpp / snake.cpp**: Logica mișcării și creșterii șarpelui.
- **painter.hpp / painter.cpp**: Desenarea elementelor vizuale.
- **abstract_painter.hpp**: Interfața pentru desenarea graficii și textului.
- **main.cpp**: Fișierul principal, punctul de intrare al aplicației.
- **.gitignore**: Fișierele care trebuie ignorate de git (ex. fișiere obiect, biblioteci, executabile).
- **Makefile**: Controale procesul de construire al aplicației.

## Contribuții

Dacă dorești să contribui la proiect, poți deschide o cerere de pull cu sugestii sau modificări.

## Licență

Acest proiect este licențiat sub licența MIT.
