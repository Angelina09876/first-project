# Изучение маркдауна  
### Изучить заголовки, абзацы, переносы  
Текст над чертой  
---  
текст под чертой <br>
новая строка

## Изучение шрифтов  
*курсив*  
_так тоже курсив_  
**полужирный**  
__так тоже полужирный__  
**полужирный _и курсив_**  
~~лишний текст~~  

## Изучение списков  
1. Пункт один  
2. Пункт два  
* Ненумерованный список пункт 1  
- Ненумерованный список пункт 2  

## Изучение ссылок
[Яндекс](https://www.yandex.ru) просто ссылка  
[Яндекс](https://www.yandex.ru "Я Yandex!") ссылка с тайтлом  

## Изучение кода  
```bash
ls -la
```  

## Изучение других возможностей  
> Здесь должна быть цитата  


`Этот текст должен быть подсвечен`  

  
|Столбец 1    | Столбец 2    | Столбец 3|  
|-------------|--------------|----------|
|text 1       | text 2       | text 3   |
|text 4       | text 5       | text 6   |  



HEAD -- это голова.  
Коммит -- это комментарий к обновленным файлам.  
Статусы файлов:  

```mermaid  
graph LR;
untracked --"git add"--> staged;
modified --"git add"--> staged;
staged --"git commit"--> tracked/commited; 
```  

