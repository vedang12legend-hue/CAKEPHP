# CAKEPHP
CakePHP is an open-source web framework written in PHP that helps developers build web applications quickly and easily. It follows the Model–View–Controller (MVC) architecture, which separates application logic, user interface, and data handling.

⚙️ Key Features

MVC Architecture – Separates logic, data, and presentation.

Convention over Configuration – Less setup and faster development.

Built-in ORM – Easily interact with databases.

Security Features – Protection against common attacks (CSRF, SQL injection).

Reusable Code – Helps developers reuse components and libraries.

💻 Common Uses

Developing dynamic websites

Building web applications

Creating REST APIs

Rapid application development (RAD)

🧠 Example CakePHP Controller Code
<?php
namespace App\Controller;

use App\Controller\AppController;

class UsersController extends AppController {
    public function index() {
        $users = $this->Users->find('all');
        $this->set('users', $users);
    }
}
?>
