# 🧮 Comparatif des Structures de Données en JavaScript, Java et Python

---

## 📦 Listes / Tableaux

| Action         | JavaScript                   | Java                           | Python               |
|----------------|------------------------------|--------------------------------|----------------------|
| Déclaration    | `let arr = [1, 2, 3]`        | `ArrayList<Integer> list = new ArrayList<>();` | `lst = [1, 2, 3]`     |
| Ajout          | `arr.push(val)`              | `list.add(val)`                | `lst.append(val)`    |
| Accès          | `arr[i]`                     | `list.get(i)`                  | `lst[i]`             |
| Suppression    | `arr.splice(i, 1)`           | `list.remove(i)`               | `lst.pop(i)` ou `del lst[i]` |
| Itération      | `for (let i of arr)`         | `for (Type i : list)`          | `for i in lst`       |
| Longueur       | `arr.length`                 | `list.size()`                  | `len(lst)`           |

---

## 🧾 Dictionnaires / Maps

| Action         | JavaScript                   | Java                           | Python               |
|----------------|------------------------------|--------------------------------|----------------------|
| Déclaration    | `let obj = {}` ou `new Map()`| `Map<K, V> map = new HashMap<>();` | `d = {}`            |
| Ajout          | `obj.key = val` / `map.set(k, v)` | `map.put(k, v)`          | `d[k] = v`           |
| Accès          | `obj.key` / `map.get(k)`     | `map.get(k)`                  | `d[k]`               |
| Suppression    | `delete obj.key` / `map.delete(k)` | `map.remove(k)`         | `del d[k]`           |
| Itération      | `for (let k in obj)` / `map.forEach()` | `for (Map.Entry<K, V> entry : map.entrySet())` | `for k, v in d.items()` |
| Taille         | `Object.keys(obj).length` / `map.size` | `map.size()`          | `len(d)`             |

---

## 🔢 Ensembles (Sets)

| Action         | JavaScript                   | Java                           | Python               |
|----------------|------------------------------|--------------------------------|----------------------|
| Déclaration    | `new Set([1,2,3])`           | `Set<T> set = new HashSet<>();`| `s = {1, 2, 3}`      |
| Ajout          | `set.add(val)`               | `set.add(val)`                 | `s.add(val)`         |
| Suppression    | `set.delete(val)`            | `set.remove(val)`              | `s.remove(val)` ou `s.discard(val)` |
| Vérif présence | `set.has(val)`               | `set.contains(val)`            | `val in s`           |
| Itération      | `for (let v of set)`         | `for (T v : set)`              | `for v in s`         |
| Taille         | `set.size`                   | `set.size()`                   | `len(s)`             |

---

## 📚 Structures Spéciales

| Structure       | JavaScript                          | Java                              | Python                        |
|-----------------|--------------------------------------|-----------------------------------|-------------------------------|
| Pile (Stack)    | `let s = []; s.push(); s.pop();`     | `Stack<T> stack = new Stack<>();` | `lst = []; lst.append(); lst.pop()` |
| File (Queue)    | `let q = []; q.push(); q.shift();`   | `Queue<T> q = new LinkedList<>();`| `from collections import deque`<br>`q = deque(); q.append(); q.popleft()` |
| File double     | `let d = new Deque()` (lib externe)  | `Deque<T> = new ArrayDeque<>();`  | `deque()` (ajout des 2 côtés) |

---

## 🧠 Remarques

- **JavaScript** : très flexible, peu typé. Idéal pour prototypage rapide.
- **Java** : très strict et typé, adapté aux environnements pro.
- **Python** : très concis, facile à lire et à écrire. Excellent pour scripts, data science, etc.

---
