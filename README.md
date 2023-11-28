Задача 44: В ячейке ниже представлен код генерирующий DataFrame, которая состоит всего из 1 столбца.
Ваша задача перевести его в one hot вид. Сможете ли вы это сделать без get_dummies?

import random
lst = ['robot'] * 10
lst += ['human'] * 10
random.shuffle(lst)
data = pd.DataFrame({'whoAmI':lst})
data.head()

![image](https://github.com/Aliana89/Home_Work_44/assets/140052202/239c8186-4a80-4622-8c51-d76b0ff97b2a)
