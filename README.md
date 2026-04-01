### Hi there

I’m Hasan Masud, a full-stack developer building scalable, user-centered, and data-driven digital products.
<br>
I use PHP/Laravel, MySQL, Python, JavaScript, Vue JS to develop the products.
<br>

- How to reach me: 
[![LinkedIn Badge](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white&link=https://www.linkedin.com/in/ihasanmasud)](https://www.linkedin.com/in/ihasanmasud)
[![Gmail Badge](https://img.shields.io/badge/-Gmail-red?style=flat&logo=gmail&logoColor=white&link=hasan.masud.dcc@gmail.com)](mailto:hasan.masud.dcc@gmail.com)

- About me:

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
                    'company' => 'ZTE Corporation',
                    'position' => 'Senior Software Developer',
                    'startDate' => '2026-02-25',
                    'endDate' => null
                ],
                [
                    'company' => 'Genex Infosys Limited',
                    'position' => 'Senior Software Developer',
                    'startDate' => '2023-11-01',
                    'endDate' => '2026-02-24'
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
