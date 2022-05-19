<template>
    <LayoutTheHeader />
    <LayoutTheMain>
        <Card like>
            <template v-slot:date>
                02 de jul, 2021
            </template>
            <template v-slot:title>Agora é oficial: o Windows 11 está vindo</template>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Officia autem iusto reprehenderit temporibus
            tempore laborum est ratione commodi molestiae? Aliquam excepturi a qui consequuntur accusantium culpa
            voluptatem hic amet animi?</p>
        </Card>
        <Card>
            <template v-slot:date>
                02 de jul, 2021
            </template>
            <template v-slot:title>Tim Berners-Lee vai leiloar código-fonte da web</template>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Officia autem iusto reprehenderit temporibus
            tempore laborum est ratione commodi molestiae? Aliquam excepturi a qui consequuntur accusantium culpa
            voluptatem hic amet animi?</p>
        </Card>
        <Card>
            <template v-slot:date>
                02 de jul, 2021
            </template>
            <template v-slot:title>Tem Firefox novo no pedaço e você vai querer migrar</template>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Officia autem iusto reprehenderit temporibus
            tempore laborum est ratione commodi molestiae? Aliquam excepturi a qui consequuntur accusantium culpa
            voluptatem hic amet animi?</p>
        </Card>
        <Card like>
            <template v-slot:date>
                02 de jul, 2021
            </template>
            <template v-slot:title>John MCAfee, criador do antivírus McAfee, morre</template>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Officia autem iusto reprehenderit temporibus
            tempore laborum est ratione commodi molestiae? Aliquam excepturi a qui consequuntur accusantium culpa
            voluptatem hic amet animi?</p>
        </Card>
    </LayoutTheMain>
</template>

<style lang="scss" scoped>
</style>