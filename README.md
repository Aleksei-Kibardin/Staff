
## описание:
```
Увы есть небольшые отклонения от дизайна макета, тк небыло опыта работы с Vuetify.
Некоторые вещи я бы переопределил, к примеру:
Адаптивность, я хотел сделать сайт адаптивным, и решил заняться этим  в последнюю очередь тк не указано в тз
я бы использовал метод бинарного поиска, но тк в основном свободное время у меня только ночь, 
я предпочел сделать так как реализовано в проэкте. И точно сделал бы по другому фильтрацию 
```
### ПРОБЛЕМЫ:
```
по какой-то причине (скорее всего по этой же не хочет открываться сайт через опен сервер) не работает пост 
в локальную базу JSON, выдает 500 поэтому я просто передаю обьект в масив который отрисовывает карточки
```
## Project setup

```
# npm
npm install

```

### Compiles and hot-reloads for development

```

# npm
npm run dev (если вдруг настройка сбросится то надо запускать на порту 8080)

# npx json-server --watch state.json


### Customize configuration

See [Configuration Reference](https://vitejs.dev/config/).
