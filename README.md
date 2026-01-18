# Integracja z KseF: Krajowy System e-Faktur.

## 📌 Opis projektu

> Wysyłanie faktur ustukturyzowanych [Fa(3)] do Ministerstwa
> Odbieranie/Pobieranie faktur oraz zarządzanie obiegiem dokumentów

- Planowanie i zarządzanie misjami dronów,
- Monitorowanie statusu oraz pozycji dronów w czasie rzeczywistym,
- Integrację z infrastrukturą IoT poprzez MQTT,
- Symulację misji dla testowania zachowania roju,
- Eksponowanie API dla zewnętrznych systemów zarządzania.

## 🛠 Technologia

### **Backend**
- PHP 8.5 (Symfony 8)
- PostgreSQL 8

## 🚀 Uruchomienie projektu

1. Start the application:

```
make start
```

2. Compile resources

```
make migrate
```

3. Run tests

```
make tests 
```
