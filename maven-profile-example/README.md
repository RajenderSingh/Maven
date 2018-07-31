## Maven Profile Example

## This example is built using Eclipse IDE with Maven

1. Download Eclipse IDE Oxygen.3a (4.7.3a) Release
 
2. Clone the repository from 

3. Import project in eclipse - Menu File –> Import –> Maven –> Existing Maven Projects

4. Browse to your source code location

5. Click Finish button to finish the importing

## Run the example

1. Add Maven build configuration 

2. Set Goal as --> clean install -Pprod

3. Run the build (it will run for prod)

## Change -Pdevto run dev env build. Similarly change -Puat and -Psit for other env builds.