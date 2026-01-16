# user Dashboard – React Task

## Layihə Məqsədi

Bu tapşırıq React əsaslarını möhkəmləndirmək üçün hazırlanmış praktik tapşırıqdır. Task yalnız tələbələrin artıq öyrəndiyi mövzuları əhatə edir.

---

## İstifadə Olunacaq Texnologiyalar

- React + Vite
- Tailwind CSS
- Component strukturu
- Props
- Array.map()

---

## Layihənin Qurulması

### 1. React layihəsinin yaradılması

```bash
npm create vite@latest
```

Layihə adı:

```
user-dashboard
```

Framework:

```
React
```

Language:

```
JavaScript
```

---

### 2. Tailwind CSS inteqrasiyası

Layihəyə Tailwind CSS mütləq şəkildə qoşulmalıdır və bütün dizayn Tailwind üzərindən yazılmalıdır.

---

## Folder Strukturu

```
src/
 ├── components/
 │     ├── Header.jsx
 │     ├── Footer.jsx
 │     ├── userList.jsx
 │     ├── userCard.jsx
 ├── App.jsx
 ├── main.jsx
```

---

## Tapşırığın Məzmunu

### Istifadəçilər üçün nümunə array

src/data folderi daxilində aşağıdakı array yaradılmalıdır:

[users](src/data/users.js)

---

## Props Məntiqi

- users array `App.jsx` komponentində saxlanılır
- Bu array props vasitəsilə `UserList` komponentinə ötürülür

Nümunə:

```jsx
<UserList data={users} />
```

---

## map() İstifadəsi

- UserList komponenti daxilində array.map() istifadə olunmalıdır
- Hər tələbə üçün ayrıca `UserCard` komponenti render edilməlidir

---

## UserCard Komponenti

Bu komponent:

- Yalnız props qəbul etməlidir
- Aşağıdakı məlumatları göstərməlidir:

- firstName
- lastName
- age
- gender
- email
- phone
- username
- image
- bank.cardNumber
- address.address
- address.city
- university
- company.name
- company.title
- role

---

## UI Tələbləri

- Bütün dizayn Tailwind CSS ilə yazılmalıdır
- Kartlar grid formatında göstərilməlidir
- Minimal dizayn elementləri:

- border
- padding
- rounded
- shadow

---

## Yekun Nəticə

Layihə işə düşəndə:

- Header görünməlidir
- user siyahısı kartlar formasında ekrana çıxmalıdır
- Footer görünməlidir
- Bütün məlumatlar props və map ilə idarə olunmalıdır

---

## Təqdimat Tələbləri

Tələbə aşağıdakıları təqdim etməlidir:

- GitHub repository linki
- Layihənin işlək screenshot-u

---

## Qiymətləndirmə

| Kriteriya              | Bal     |
| ---------------------- | ------- |
| Vite qurulması         | 20      |
| Tailwind inteqrasiyası | 20      |
| Component strukturu    | 20      |
| Props istifadəsi       | 20      |
| map() istifadəsi       | 20      |
| **Cəmi**               | **100** |

---

Uğurlar!
