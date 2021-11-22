require __DIR__ . '/../vendor/autoload.php';
require __DIR__ . '/../vendor/yiisoft/yii2/Yii.php';

// load application configuration
$config = require __DIR__ . '/../config/web.php';

// instantiate and configure the application
(new yii\web\Application($config))->run();
