```c#        
<div class="form-group">
    @Html.LabelFor(model => model.tarea.estado, htmlAttributes: new { @class = "control-label col-md-2" })
    <div class="col-md-10">
        @Html.EnumDropDownListFor(model => model.tarea.estado, htmlAttributes: new { @class = "form-control" })
        @Html.ValidationMessageFor(model => model.tarea.estado, "", new { @class = "text-danger" })
    </div>
</div>
```
