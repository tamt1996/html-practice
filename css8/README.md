[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/2rVpS6-W)

# დავალება: CSS Fundamentals

## აღწერა

თქვენი დავალებაა მოცემული დიზაინის აწყობა HTML და CSS ტექნოლოგიების გამოყენებით.
მთავარი მიზანია სუფთა, ვალიდური და ადვილად წაკითხვადი კოდის დაწერა, რომელიც ვიზუალურად მაქსიმალურად ზუსტად გაიმეორებს Figma-ში მოცემულ დიზაინს.

🔗 **Figma Link:** [POS Restaurant UI System](https://www.figma.com/design/itqAVhJDIn39O3pYHuftbz/POS-restaurant-UI-system--Community-?node-id=0-1&p=f&t=f4Rg2a8ONnbGR6Ax-0)

## ტექნიკური მოთხოვნები

1. **Semantic HTML**
გამოიყენეთ სემანტიკური HTML თეგები, მაგალითად:
`<header>`, `<main>`, `<section>`, `<footer>`, `<button>`

არ გამოიყენოთ ზედმეტი `<div>` ელემენტები იქ, სადაც სემანტიკური თეგი უფრო სწორია.

2. **Selector Specificity**
სტილიზაციისთვის გამოიყენეთ `class`.

მოერიდეთ ელემენტის თეგებით სტილიზაციას, მაგალითად `div p`, `section h1`.

მოერიდეთ `id`-ებით სტილიზაციას, რათა კოდი იყოს მარტივად წასაკითხი და გასაფართოებელი.

3. **Unique IDs**
ყველა `id` უნდა იყოს უნიკალური.

ერთ გვერდზე არ უნდა არსებობდეს ორი ერთნაირი `id`.

4. **Naming**
კლასებისა და `id`-ების სახელები უნდა იყოს:
- აღწერითი
- ინგლისურ ენაზე

მაგალითად:
- `card-title`
- `main-navigation`

არასწორი მაგალითები:
- `box1`
- `test`
- `div2`

5. **Selectors**
გამოიყენეთ class-ები სტილიზაციისთვის.

ელემენტების თეგებით (`p`, `h1`, `div`) სტილიზაცია რეკომენდებული არ არის.

6. **Pseudo-classes**
გამოიყენეთ pseudo-class-ები, მაგალითად:
- `:hover`
- `:active`
- `:focus`

7. **Pseudo-elements**
გამოიყენეთ pseudo-element-ები, მაგალითად:
- `::before`
- `::after`
- `::first-letter`
- `::first-line`

## README Requirement

აუცილებელია, რომ `README.md` ფაილში ჩანდეს თქვენი ნამუშევრის ვიზუალი.

ინსტრუქცია:
1. გადაიღეთ აწყობილი გვერდის სქრინშოთი.
2. დაარქვით ფაილს `preview.png`.
3. ატვირთეთ ეს სურათი თქვენს GitHub რეპოზიტორიაში.
4. ჩასვით სურათი `README.md` ფაილში.

## Acceptance Criteria

- ვიზუალი შეესაბამება Figma-ს დიზაინს
- HTML სტრუქტურა სემანტიკურად სწორია
- CSS სტილიზაცია ხდება class-ებით
- არ გვხვდება დუბლირებული `id`-ები
- `README.md` ფაილში ჩანს ნამუშევრის preview
