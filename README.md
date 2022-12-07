```php
<?php
namespace L3moon;
class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Veganext',
                'position' => 'CyberSecurity Specialist'         
            ]
        ];
    }
    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Java::class,
            Web_Exploitaion::class,
            Penetration_Testing::class,
            C::class,
            Azure::class,
            Aws::class,
        ];
    }
    public function getFutureGoal(): string
    {
        return '100 CVEs';
    }
    public function getContact(): array
    {
        return [
            'email' => 'contact@l3moon.me',
            'twitter' => '@le3moon',
            'Blog' => 'https://l3moon.me/',
            'Linkedin' => 'https://www.linkedin.com/in/aminelsassi/',
        ];
    
}
```
