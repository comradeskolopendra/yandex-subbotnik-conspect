# Стартанули.

# Безопасная песочница.
Песочница - исполнение пользовательского кода.
Защита исполнения польз. кода.

ShadowRealms - не вылезает за пределы iframe.
В ноде есть vm модуль для изоляции польз. кода.
vm - позволяет изолировать контекст.

constructor.cinstructor("this")().exit() - подняилсь чуть повыше в прототипе. - global
constructor.constructor === Function;

vm - не защитный механизм, а способ разделять контексты.

vm2 - уже защитная, можно делать безопасный сандбокс. Работает с помощью proxy.

vm2 - уже не позволяет вылести из контекста, в отличии от vm.
vm2 больше нет.

vm2 | vm - в одном memory heap.

v8 isolate - позволяет изолировать memory heap в одном v8 process.
isolavted-vm - позволяеть изолировать так же memory heap с ограничением памяти. // можно забыть //

// quick js - js virutal machine.
// quick js - must have.
// quick js-emscripten - связка между wasm и js/ts.

// что такое lambda-functions?
// НЕ ПОНЯЛ КОНЦЕПТ WASM.

// не понял quick.js-emscripten.


interop - все базовые типы.

spectre - unfixable проблема. 

// spectre = ?

// песочнику построить можно, но сложно. вопросы к безопасности, много дырок.
// quick js - новый движок.
// с wasm можно строить песочницы.