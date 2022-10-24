# Markdown

Markdown is simple and easy-to-use markup language uses to format virtually any document.

## Headers

# H1

## H2

### H3

#### H4

##### H5

###### H6

## Html

```html
    <p></p>
    <ul>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
    </ul>
    <p></p>
```


## C++

```cpp
#include <iostream>

int readNumber()
{
    std::cout << "Enter a number: ";
    int x {};
    std::cin >> x;
    return x;
}

void writeAnswer(int x)
{
    std::cout << "The answer is " << x << '\n';
}

int main()
{
    int x { readNumber() };
    int y { readNumber() };
    writeAnswer(x + y); 
    return 0;
}
```

```python
    def 
```


**This text is bold**

_This text is italicized_


## Lists

### Ordered List

Favorite fruits

1. Apple
2. Strawberry
3. Mango


### Unordered List

- item 1
- item 2
- item 3


### Link

- [Learn web development](https://developer.mozilla.org/en-US/docs/Learn)
- [Everything you need to learn Markdown.](https://www.markdownguide.org/)

### Images

![An image](./myImage.jpg)

Todo

- [x] Learn HTML
- [ ] Learn CSS
- [ ] Learn JS

<!-- this is a comment -->
