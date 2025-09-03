# Środowisko Egzaminacyjne - React

## Informacje ogólne
Na komputerach egzaminacyjnych **BĘDZIE JUŻ ZAINSTALOWANE** środowisko do tworzenia aplikacji webowych. **NIE MUSISZ TEGO ROBIĆ SAM** Będziesz miał jedną z opcji. Musisz umieć uruchomić projekt React.

## Opcja 1: Vite

Vite to nowoczesne narzędzie do szybkiego tworzenia aplikacji React. Oferuje szybsze kompilowanie i lepsze doświadczenie deweloperskie.

### Instalacja i uruchomienie:
```bash
# Utwórz nowy projekt React z szablonem Vite
npm create vite@latest my-app-name --template react

# Przejdź do katalogu projektu
cd my-app-name

# Zainstaluj zależności
npm install

# Uruchom serwer deweloperski
npm run dev
```

## Opcja 2: Create React App

Create React App to klasyczne narzędzie do tworzenia aplikacji React, stabilne i sprawdzone.

### Instalacja i uruchomienie:
```bash
# Utwórz nowy projekt React
npx create-react-app my-app

# Przejdź do katalogu projektu
cd my-app

# Uruchom serwer deweloperski
npm start
```



## Bootstrap

Bootstrap będzie już zainstalowany na komputerach egzaminacyjnych za pomocą:

```bash
npm install bootstrap
```

### Dodawanie Bootstrap do projektu:

**Dla Vite** - dodaj w pliku `main.jsx`:
```jsx
import 'bootstrap/dist/css/bootstrap.min.css'
import 'bootstrap/dist/js/bootstrap.bundle.min.js'
```

**Dla Create React App** - dodaj w pliku `index.js`:
```jsx
import 'bootstrap/dist/css/bootstrap.min.css'
import 'bootstrap/dist/js/bootstrap.bundle.min.js'
```

## Struktura projektu
Po utworzeniu projektu otrzymasz gotową strukturę plików z przykładową aplikacją React, którą możesz od razu uruchomić i modyfikować według wymagań egzaminu.
