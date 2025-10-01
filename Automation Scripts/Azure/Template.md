# Azure (Azure Function, Python)

```
import azure.functions as func

def main(req: func.HttpRequest) -> func.HttpResponse:
    print("Hello World from Azure!")
    return func.HttpResponse("Hello World from Azure!")
```
