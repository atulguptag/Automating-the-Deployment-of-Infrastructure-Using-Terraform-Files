## Run the following Commands in cloud shell terminal.

```
terraform --version

mkdir tfinfra

cd tfinfra

touch provider.tf

nano provider.tf
```

* Put `provider.tf` code into the *provider.tf* file.

* To save the file press `Ctrl + X, Y` and then hit `ENTER`.

* Initialize the code using init command.

```
terraform init
```

* Create `mynetwork.tf` file.

```
touch mynetwork.tf 

nano mynetwork.tf
```

* Put `mynetwork.tf` code into the *mynetwork.tf* file.

* To save the file press `Ctrl + X, Y` and then hit `ENTER`.

```
mkdir instance

cd instance

touch main.tf

nano main.tf
```
* Put `main.tf` code into the *main.tf* file.

* To save the file press `Ctrl + X, Y` and then hit `ENTER`.

```
touch variables.tf

nano variables.tf 

cd -
```
* Put `variables.tf` code into *variables.tf* file.

* To save the file press `Ctrl + X, Y` and then hit `ENTER`.

* Now, it's time to run the below commands.

```
terraform fmt

terraform init

terraform plan

terraform apply
```

# Congratulations🎉! You're done with this lab.