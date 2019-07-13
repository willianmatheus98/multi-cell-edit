# Multi-cell-edit

this is a alternative to Datatables multi-row edit

## Usage

## get cells selecteds
```javascript
$(".selected");
```

## change cells selecteds
```javascript
$(".selected").each(function(index, item) {
                var celula = $(item);
                var antigoValor = decimalValue(celula.html());
                var novoValor = 10.00;
                celula.html(formataDinheiro(novoValor.toFixed(2)));
                celula.addClass("edited");
});
```
