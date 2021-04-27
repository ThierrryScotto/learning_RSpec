#Using test with ruby

command to create file with config using RSPEC
rspec --init

command to run the test
rspec <file_path>

command to run the test with documentation
rspec <file_path> -f d

command to stop when there is a error
rspec <file_path> --fail-fast

equal? and eql? | this is function not are the same thing:
equal: compare to see if the object is ta same object
eql: see the information inside in the variable

# hooks

- executa a cada bloco
before(:example) do
  @car = Car.new
end

- executa uma vez
before(:context) do
  @car = Car.new
end