# things-tristate-radio

## yes 혹은 no 데이터를 선택하여 value 값을 전달해 준다.


## Example:

```html
    <things-tristate-radio
      value="{{textconfirm}}"
      label="label">
    </things-tristate-radio>
    <div>
      Result:"[[textconfirm]]"
    </div>
```

`things-tristate-radio-value-changed` event 발생


*****
</br></br>


## Dependencies

Element의 종속성은 [Bower](http://bower.io/)를 통해 관리되며, 아래의 방법을 통해 설치할 수 있다.

    npm install -g bower

다음, element의 종속성을 다운로드한다.

    bower install

## Playing With Your Element

element를 독립적으로 처리하려면 [Polyserve](https://github.com/PolymerLabs/polyserve)를 사용하여 element의 bower 의존성을 유지하도록 하며, 이는 아래의 방법을 통해 설치할 수 있다.

    npm install -g polymer-cli

그리고, 아래의 방법을 통해 실행할 수 있다.

    polymer serve

element를 실행한 경우, `things-tristate-radio`가 디렉토리 이름으로 포함되어 있는 `http://localhost:8080/components/things-tristate-radio/`를 통해 이를 미리 확인할 수 있다. 
