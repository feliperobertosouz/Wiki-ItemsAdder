# Corrigir problema com blocos

{% hint style="warning" %}
Blocos do **MMOItems** não são compatíveis com **ItemsAdder** e vice-versa.
{% endhint %}

## Como usar os blocos do MMOItems?

Você precisa abrir o arquivo `config.yml` do **ItemsAdder** e desativar os blocos **REAL** (cogumelo).

{% code title="config.yml" %}
```yaml
  disable-REAL: true
```
{% endcode %}

{% hint style="info" %}
Após aplicar essa alteração, você não poderá mais criar blocos do ItemsAdder do tipo: REAL.

Outros tipos personalizados de blocos do ItemsAdder ainda funcionarão (por exemplo, REAL_NOTE).
{% endhint %}
