
 ![panda](https://github.com/Aliana89/Home_Work_44/assets/140052202/dd6a39c3-1b97-4915-8a05-19a2f4b805e0)

 В ячейке ниже представлен код генерирующий DataFrame, которая состоит всего из 1 столбца.
Ваша задача перевести его в one hot вид. Сможете ли вы это сделать без get_dummies?

import random
lst = ['robot'] * 10
lst += ['human'] * 10
random.shuffle(lst)
data = pd.DataFrame({'whoAmI':lst})
data.head()
![image](https://github.com/Aliana89/Home_Work_44/assets/140052202/37590e5b-2201-41ff-a85e-cfac1e8256ba)


