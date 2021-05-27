# Task 2

#### 1. Make the code below cleaner, better and reusable

```php
# Add leading 0 number
# ex: 5 => 0005
private function convertNumber($number) {
    Strlen($number)===1?'000+$number : Strlen($number)===2?'00+$number :
Strlen($number)===3?'0+$number );
    return $number;
}

convertNumber(5);
```

#### 2. After change the code, make a pull request
