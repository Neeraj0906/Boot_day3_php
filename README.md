# Boot_day3_php
<?php

function printMultiplicationTable($number) {
    for ($i = 1; $i <= 10; $i++) {
        $result = $number * $i;
        echo "$number x $i = $result" . PHP_EOL;
    }
}

$givenNumber = 5;
printMultiplicationTable($givenNumber);

?>
