# Yarmolik Anastasiya

## Contact Information

* Location: Minsk, Belarus

* E-mail: yormolik.anastasiya@gmail.com

* Telegram: @justdottt 

* [GitHub](https://github.com/Nastya404)

* [LinkedIn](linkedin.com/in/-yarmolik-anastasiya)

## About me

Energetic and highly communicative individual with a talent for creative, out-of-the-box problem solving. My goal is to dive into web development and grow into a strong specialist in the field. I thrive in collaborative environments, bridging the gap between technical requirements and clear communication with team members and clients. 

## Skills

* JavaScript (ES6+) & TypeScript

* HTML5, CSS3, SASS

* Webpack, npm, Chrome DevTools

* Git, Github

* Testing: Jest (Experience with writing robust Unit Tests to ensure code
stability)

* Agile Methodologies: Scrum, Kanban, Agile

* UI/UX Collaboration: Figma (Skilled in translating design mockups and
prototypes into pixel-perfect code)

## Code Examples

This function filters a list of goods based on a price range defined by ` floorPrice ` (minimum) and ` ceilPrice ` (maximum).

```
export const priceFilter = (goods, floorPrice, ceilPrice) => {
    return goods.filter(goodsItem =>{
        if(floorPrice === '' && ceilPrice === '') return goodsItem;
        else{
        const min = (floorPrice === '' ? 0 : Number(floorPrice));
        const max = (ceilPrice === '' ? Infinity : Number(ceilPrice));
        return goodsItem.price >= min && goodsItem.price <= max;
        }  
    });
};

```

## Experience

[Interactive color model converter (RGB ↔ XYZ ↔ HLS)](https://github.com/Nastya404/Color-picker)

The "Color Model Converter" web application is an interactive tool for converting colors between three different color spaces: RGB, XYZ, and HLS. The application operates in real-time, instantly recalculating values across all models whenever any parameter is changed.

### Стек технологий:

* HTML5
* CSS3
* Vanilla JS

## Education

* University: Belarusian State University, bachelor of applied computer science

* Courses:

    - [JavaScript Manual](https://learn.javascript.ru/)

    - [HTML Academy](https://htmlacademy.ru/)

    - [JavaScript for beginners](https://stepik.org/course/2223/info)

## Languages 

* English - C2 Proficient ([EF SET](https://cert.efset.org/mYv5ME))

* Russian - Native

* Belarussian - Native







