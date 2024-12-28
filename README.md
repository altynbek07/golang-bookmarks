
# Golang Bookmarks
A simple Go project for managing bookmarks. The application allows users to add, view, and delete bookmarks. Each bookmark has a name as its key and a URL as its value.

## Features
- **Add Bookmarks**: Add a new bookmark with a name and a corresponding URL.
- **View Bookmarks**: List all the saved bookmarks.
- **Delete Bookmarks**: Remove a bookmark by its name.

## Requirements
- Go (version specified in `go.mod`)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/altynbek07/golang-bookmarks.git
   ```

2. Navigate to the project directory:
   ```bash
   cd golang-bookmarks
   ```

2. Build the project:
   ```bash
   go build -o bookmarks
   ```

3. Run the application:
   ```bash
   ./golang-bookmarks
   ```

## Usage

After running the application, you can interact with it through the console:

- **Add a bookmark**:
  Enter the name and URL when prompted.
- **View bookmarks**:
  The application will list all saved bookmarks.
- **Delete a bookmark**:
  Enter the name of the bookmark you want to delete.

## Example

```bash
Приложения для закладок

1. Посмотреть закладки
2. Добавить закладку
3. Удалить закладку
4. Выход
Выберите вариант 2
Введите название: Google
Введите ссылку: https://google.com

Выберите вариант 1
Google: https://google.com

Выберите вариант 3
Введите название: Google

Выберите вариант: 4
```

## Author
Altynbek Kazezov

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
