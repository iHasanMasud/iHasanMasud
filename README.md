### Hi there 👋

I'm [Hasan Masud](http://hasanmasud.com/), a fullstack developer building digital products at my current workplace using Lean Design principles.
<br>
I use PHP/Laravel, MySQL, JavaScript, Vue JS, jQuery, Bootsrap & Tailwind css to develop the products.
<br>

- 📫 How to reach me: 
[![LinkedIn Badge](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white&link=https://www.linkedin.com/in/ihasanmasud)](https://www.linkedin.com/in/ihasanmasud)
[![WhatsApp Badge](https://img.shields.io/badge/-WhatsApp-tealgreen?style=flat&logo=whatsApp&logoColor=white&link=https://wa.me/8801720204272)](https://wa.me/8801720204272)
[![Telegram Badge](https://img.shields.io/badge/-Telegram-blue?style=flat&logo=telegram&logoColor=white&link=https://t.me/iHasanMasud)](https://t.me/iHasanMasud)
[![Gmail Badge](https://img.shields.io/badge/-Gmail-red?style=flat&logo=gmail&logoColor=white&link=hasan.masud.dcc@gmail.com)](mailto:hasan.masud.dcc@gmail.com)

- 💬 A little more about me:

```php
<?php

namespace HasanMasud;

class About extends Me
{
    public function getWorkplaces(): array
    {
        return [
            'workplaces' => [
                [
                    'company' => 'Genex Infosys Limited',
                    'position' => 'Senior Software Developer',
                    'startDate' => '2023-11-01',
                    'endDate' => null
                ],
                [
                    'company' => 'DigiPro Solutions Ltd.',
                    'position' => 'Senior Software Developer',
                    'startDate' => '2022-10-06',
                    'endDate' => '2023-10-31'
                ],
                [
                    'company' => 'Excel Telecom (Pvt.) Ltd.',
                    'position' => 'Full-Stack Developer',
                    'startDate' => '2021-10-02',
                    'endDate' => '2022-10-04'
                ],
                [
                    'company' => 'Aqa Technology',
                    'position' => 'Full-Stack Developer',
                    'startDate' => '2018-04-01',
                    'endDate' => '2021-09-30'
                ]
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [Laravel::class, Vuejs::class, Python::class, Django::class, MongoDB::class];
    }
}

```
