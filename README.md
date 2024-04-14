
# Revisão de Computação II Java


1. Implemente a interface `Comparable` que possui o método abstrato `int compareTo(Comparable other)`.

2. Implemente a classe `Collections` que contém o método de ordenação público:

    ```java
    static void selectionSort(ArrayList<Comparable> array);
    ```

3. Desenvolva uma classe chamada `Transport` para representar um veículo de transporte. Essa classe deverá implementar a interface `Comparable`. A classe possui cinco atributos, denominados:

    - `name`: nome do veículo de transporte, do tipo `String`;
    - `height`: altura do veículo de transporte em metros (m), do tipo `double`;
    - `length`: comprimento do veículo de transporte em metros (m), do tipo `double`;
    - `payload`: capacidade de carga do veículo de transporte em toneladas (t), do tipo `int`;
    - `speed`: velocidade do veículo de transporte em quilômetros por hora (km/h), do tipo `int`.

    Além disso, essa classe deve implementar o método `compareTo` baseado na velocidade do veículo.

4. Estenda a classe `Transport` para implementar uma classe chamada `AirTransport` para representar um veículo de transporte aéreo. A classe possui dois atributos, denominados:

    - `range`: autonomia de voo do veículo de transporte aéreo em quilômetros (km), do tipo `int`;
    - `wingspan`: envergadura da asa do veículo de transporte aéreo em metros (m), do tipo `double`.

5. Estenda a classe `Transport` para implementar uma classe chamada `LandTransport` para representar um veículo de transporte terrestre. A classe possui dois atributos, denominados:

    - `engine`: motor do veículo de transporte terrestre, do tipo `String`;
    - `wheels`: rodas do veículo de transporte terrestre, do tipo `String`.

6. Estenda a classe `Transport` para implementar uma classe chamada `WaterTransport` para representar um veículo de transporte marítimo. A classe possui dois atributos, denominados:

    - `beam`: boca do veículo de transporte marítimo em metros (m), do tipo `int`;
    - `draught`: calado do veículo de transporte marítimo em metros (m), do tipo `int`.

7. Desenvolva uma classe chamada `Catalog` para representar um catálogo de veículos de transporte, implementando os métodos para inserção e apresentação dos veículos de transporte cadastrados de forma ordenada.
