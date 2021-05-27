Kondisi Digunakan Banyak

echo 'Nilai Anda: '.($score > 10 ? ($age > 10 ? 'Rata-Rata' : 'Luar Biasa') : ($age > 10 ? 'Buruk' : 'Rata-Rata') );

private function convertNumber($number) {
(strlen($number) === 1 ? $number = '000' +q $number : strlen($number) === 2 ? $number = '00' + $number : strlen($number) === 3 ? $number = '0' + $number);
    return $number;


convertNumber(5);
