# AdvancedEnchantments

## [Download here](https://www.spigotmc.org/resources/43058/)

## Como usar os encantamentos

Esse é um exemplo de configuração para um item customizavel do ItemsAdder com encantamento.

{% hint style="warning" %}
Isso requer **ItemsAdder** 2.5.2+
{% endhint %}

```yaml
  ruby_pickaxe:
    display_name: display-name-ruby_pickaxe
    permission: ruby_pickaxe
    resource:
      material: DIAMOND_PICKAXE
      generate: true
      textures:
      - item/ruby_pickaxe.png
    enchants:
    - ambit:7
```
