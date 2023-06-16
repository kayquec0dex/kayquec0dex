```php
class Attributes extends Kayque {
    public static function contact() {
        $discord = "polakznx";
        $instagram = "@ssilvakayque";

        return array($discord, $instagram);
    }

    public static function life() {
        $langs = array('português', 'inglês');
        $age = 19;

        return array($langs, $age);
    }

    public static function coding() {
        $langs = array('php', 'javascript');
        $specialities = array('web/app reverse engineering', 'fullstack');
        $environnement = array('vscode');

        return array($langs, $specialities, $environnement);
    }
}
