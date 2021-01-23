# working-with-my-packages
Для того чтобы работать со своими пакетами нужно создать для них папки с такими же названиями и вызывать в главном пакете, например: 

package main

import (
    "./db"
    "./log"
)

func main() {
    db.HelloDB()
    log.HelloLog()
}
