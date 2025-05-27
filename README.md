# trabalho-de-flutter

Organize o projeto em camadas para facilitar a manutenção:

lib/
models/: Entidades (user.dart, task.dart, category.dart).
data/: Banco de dados e repositórios (database_helper.dart, user_repository.dart, task_repository.dart, category_repository.dart).
controllers/: Lógica de negócios (user_controller.dart, task_controller.dart, category_controller.dart).
screens/: Telas da UI (login_screen.dart, registration_screen.dart, task_list_screen.dart, add_edit_task_screen.dart, task_details_screen.dart, reports_screen.dart).
main.dart: Ponto de entrada.
