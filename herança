<?php
class Funcionario {
    public string $nome;
    public float $salariobase;
    public function __construct(string $nome,float $salariobase) {
        $this->nome = $nome;
        $this->salariobase=$salariobase;
    }

    public function calcularSalario(): float{
        return $this->salariobase;
    }
}

class Gerente extends Funcionario {
    public float $bonus;
    public function __construct(string $nome,float $salariobase,float $bonus) {
        parent::__construct($nome, $salariobase); 
        $this->bonus=$bonus;
        
    }

    public function calcularSalario(): float {
        return $this->salariobase * $this->bonus;
    }
}

$meugerente = new Gerente("Rex",2000,2);

echo $meugerente->calcularSalario(); 
echo "<br>";

  
?>
