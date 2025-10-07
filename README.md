# 🧠 ARiSC Safari Zone

## 📋 Opis projektu
Projekt **ARiSC Safari Zone** stanowi opracowanie i implementację środowiska do **Uczenia ze Wzmocnieniem (Reinforcement Learning)** z wykorzystaniem biblioteki **Gymnasium**.  
Środowisko odwzorowuje tryb *Safari Zone* znany z gier Pokémon i pozwala agentom podejmować decyzje takie jak rzucanie przynęty, kamieni lub prób łapania Pokémona.

Celem projektu było stworzenie w pełni funkcjonalnego środowiska oraz wytrenowanie agenta zdolnego do opracowania skutecznej strategii w grze z elementami losowymi.

---

## 🎯 Cele projektu
- Implementacja środowiska w stylu *Safari Zone* w oparciu o bibliotekę **Gymnasium**.  
- Analiza i porównanie dwóch algorytmów uczenia ze wzmocnieniem: **DQN** i **PPO**.  
- Zbadanie wpływu systemu nagród i kar na proces uczenia agenta.  
- Ocena efektywności strategii w środowisku o częściowo losowym charakterze.

---

## 📊 Wyniki eksperymentów
W trakcie testów porównano zachowanie agenta losowego oraz agentów wytrenowanych przy użyciu algorytmów **DQN** i **PPO**.  
Ze względu na losowy charakter gry wyniki przedstawiają wartości **średnie**.

| Typ agenta | Średnia liczba złapanych Pokémonów (na 30) |
|-------------|--------------------------------------------|
| Losowy agent | 7.6 |
| PPO (wytrenowany) | 11 |
| DQN (wytrenowany) | 20 |

Agent oparty o **DQN** znacząco przewyższył pozostałe strategie, ucząc się efektywnego zarządzania zasobami i podejmowania decyzji w warunkach niepewności.  
Zaprojektowany system nagród zachęcał do stosowania taktyk, zamiast przypadkowego zużywania wszystkich Safari Ball.
