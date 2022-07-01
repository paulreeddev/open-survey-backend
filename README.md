[Demo](http://170.187.203.187/login)

# open-survey

open-survey is a simple survey collection tool that allows the user to create dynamic forms which is mostly used by companies, researchers or Individual to capture a given set of data without creating website or application.

This repo is the backend, for the frontend go to [here](https://github.com/paulreeddev/open-survey)

This Project is made possible by

<table>
<tr><td>
            <a href="https://www.linode.com/"><img src="https://www.linode.com/wp-content/uploads/2021/01/Linode-Logo-Black.svg" /></a>
        </td>
        </tr>
        <tr>
        <td>
            <a href="https://hashnode.com/"><img src="https://cdn.hashnode.com/res/hashnode/image/upload/v1592751328987/VzrtgcQNF.jpeg" /></a>
        </td>
    </tr>

## Requirements

You need to have PHP version **8.1** or above. Node.js version **12.0** or above.

## Installation

#### Backend

1. Clone the project
2. Go to the project root directory
3. Run `composer install`
4. Create database
5. Copy `.env.example` into `.env` file and adjust parameters
6. Run `php artisan serve` to start the project at http://localhost:8000

#### Frontend

1. Navigate to `vue` folder using terminal
2. Run `npm install` to install vue.js project dependencies
3. Copy `vue/.env.example` into `vue/.env` and specify API URL
4. Start frontend by running `npm run dev`
5. Open http://localhost:3000

## License

The project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
