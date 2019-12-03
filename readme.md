# Eloquent object relations

## Install
```
composer require mistery23/eloquent-object-relations
```
Using
---
```
use WebSystemsSolutions\EloquentObjectRelations\HasObjectRelations;

class User extends Model
{
    use HasObjectRelations;
    ....
}
```