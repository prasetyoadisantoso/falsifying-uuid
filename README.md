# FALSIFYING UUID
Simple encryption with caesar chiper method to falsifying the UUID and extra security. 
Match with [Ramsey UUID](https://github.com/ramsey/uuid) or [Webpatser UUID](https://github.com/webpatser/laravel-uuid)

### Installation
composer require pras/falsifying-uuid

### Usage:
Encrypt with parameter (UUID, (int)key):
```
$false = \Pras\Falsifying\Falsifying::falsify("1a2b3c-2e3b4d-3a4g5g-4j5t6o-5i6u7b", 5);
```

Decrypt with parameter (Falsified UUID, (int)key):
```
$true = \Pras\Falsifying\Falsifying::truthy($false, 5);
```
