---
description: ItemsAdder is compatible with MMOItems and it's very easy to integrate.
---

# MMOItems

Baixe **MMOItems** [aqui](https://www.spigotmc.org/resources/mmoitems-premium.39267/)

### Aqui você pode baixar o pacote de exemplo mostrado neste tutorial

{% embed url="https://www.spigotmc.org/resources/items-mmoitem-example-integration.88351/" %}

## Limitações conhecidas

{% embed url="https://github.com/PluginBugs/Issues-ItemsAdder/issues/2008" %}

## Conecte um MMOItem a um item do ItemsAdder

### Use o comando /mmoitems browse

![](<../../../.gitbook/assets/image_(25).png>)

### Crie um novo MMOItem

![](<../../../.gitbook/assets/image_(26).png>)

![](<../../../.gitbook/assets/image_(29).png>)

### Adicione todos os atributos que desejar, por exemplo, dano mágico etc.

![](<../../../.gitbook/assets/image_(28).png>)

### Visualização do MMOItem dentro de /mmoitems browse

![](<../../../.gitbook/assets/image_(30).png>)

### Crie seu arquivo .yml como de costume e adicione todas as propriedades para o item do ItemsAdder

`ItemsAdder/contents/mmoitems_example/configs/example.yml`

{% hint style="success" %}
Como você pode ver, defini um novo atributo chamado **`mmoitem`** e também **`type`** e **`id`**.\
Esses são usados para **conectar** os **dois itens**.
{% endhint %}

```yaml
info:
  namespace: mmoitems_example
items:
  test:
    display_name: ""
    permission: example_item
    mmoitem:
      type: SWORD
      id: TEST
    resource:
      material: DIAMOND_SWORD
      generate: true
      textures:
      - item/test.png
    durability:
      max_custom_durability: 1324
```

### Crie sua textura .png como de costume

`ItemsAdder/contents/mmoitems_example/resourcepack/mmoitems_example/textures/item/test.png`

### Obtenha o item

Utilize o comando `/iaget mmoitems_example:test` para obter o seu item finalizado

![](<../../../.gitbook/assets/immagine (97).png>)

![](<../../../.gitbook/assets/immagine (25).png>)
