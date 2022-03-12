1. indexOf(): 찾은 값의 첫번째 **원소의 위치를 반환**해주며, 없을경우 -1을 리턴합니다.<br>
numbers = [1,2,3,4,5]
indexOf(2) = 1
indexOf(0) = -1

2. includes(): true / false 로 있다, 없다를 직관적으로 리턴해줍니다.<br>
numbers = [1,2,3,4,5]
includes(2) = true
includes(0) = flase

3. find():  해당 조건에 만족하는 **첫 번째 요소의 값을 반환**하며 만족하지 않으면 undefined를 반환합니다.<br>
numbers = [1,2,3,4,5]
find(v => v > 1) = 2
find(v => v == 0) = undefined

4. findIndex():  findIndex 메서드는 해당 조건에 만족하는 첫 번째 요소의 **인덱스를 반환**하며 만족하지 않으면 -1을 반환합니다.<br>
numbers = [1,2,3,4,5]
find(v => v > 1) = 1
find(v => v == 0) = -1

5. filter():  filter 메서드는 해당 조건에 만족하는 **요소를 모은 새로운 배열을 반환**합니다.<br>
numbers = [1,2,3,4,5]
find(v => v > 1) = [2,3,4,5]
find(v => v > 6) = []
