# README


## Set up the database
```
  Rails db:create db:migrate
```

## Run the application
```clickhouse
  Rails s

```

## For Post api

``/retro_info?retro=10``

Body:
 ```
 {
        "well": {
            "0": {
                "value": "Story planning"
            },
            "1": {
                "value": "Story Pointing"
            },
            "2": {
                "value": "Reviews"
            }
            
        },
         "notwell": {
            "0": {
                "value": "Code reviews"
            }
            
        },
         "continue": {
            "0": {
                "value": "Code review"
            },
            "1": {
                "value": "Story planning"
            }
            
        },
         "improve": {
            "0": {
                "value": "Code reviews"
         }
    }
            
    }
    
```
    
    
## For Get api
```clickhouse
  /retro_info?retro=10
```

