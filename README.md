# IntelliasGo-animal-farm-interface

- створити PR до ферми
- додати функцію, яка буде приймати параметр інтерфейсного типу і виконує в собі мати 3 етапів валідації.
- кожен етап валідації - окрема функція що має повертати помилку
1. валідація 1 - чи співпадає тип тварини з тим як вона називаєтсья
2. валідація 2 - чи важить тварина меньше норми
3. валідація 3 - чи є тварина їстівною
- якщо сталася помилка -  обгорнути її  на кожному етапі, додавши інформації як у прикладі.
- викликати валідацію перед тим як рахувати загальну кількість корму для ферми
- якщо сталася помилка - вивести її і припинити виконання програми
## вкладеність помилки має бути:
- помилка конкретної валідації
- що саме пійшло не так
- сказати що тварина не пройшла валідацію
- утонити для якої тварини провалена перевірка
