# JavaScript Array Methods

This Repository contains all the major array methods for Javascript.
Do Star it and Contributions are welcomed.


## Find
```javascript
[3,4,5,6].at(1); //4
```

## Pop
```javascript
[3,4,5,6].pop(); //[3,4,5]
```

## Push
```javascript
[3,4,5,6].push(7); //[3,4,5,6,7]
```

## Fill
```javascript
[3,4,5,6].fill(1); //[1,1,1,1]
```

## Join
```javascript
[3,4,5,6].join("-"); // '3-4-5-6'
```

## Shift
```javascript
[3,4,5,6].shift(); // [4,5,6]
```

## Reverse
```javascript
[3,4,5,6].reverse(); // [6,5,4,3]
```


## Unshift
```javascript
[3,4,5,6].unshift(1); //[1,3,4,5,6]
```

## Includes
```javascript
[3,4,5,6].includes(5); //true
```


## Map
```javascript
[3,4,5,6].map((num) => num + 6); // [9,10,11,12]
```

## Find
```javascript
[3,4,5,6].find((num) => num > 4); // 5
```


## Filter
```javascript
[3,4,5,6].filter((num) => num > 4); // [5,6]
```

## Every
```javascript
[3,4,5,6].every((num) => num > 5); //false
```


## Find Index
```javascript
[3,4,5,6].findIndex((num) => num > 4); //2
```

## Reduce
```javascript
[3,4,5,6].reduce((acc, num) => acc + num,0) //18
```
## Contributing

Pull requests are welcome. Want to add any other Methods, welcomed

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
