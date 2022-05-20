<template>
    <LayoutTheHeader />
    <LayoutTheMain>
        <Card like>
            <template v-slot:date>20 de mai, 2021</template>
            <template v-slot:title>Android 13 beta will test out-of-the-box support for most braille displays</template>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Officia autem iusto reprehenderit temporibus
                tempore laborum est ratione commodi molestiae? Aliquam excepturi a qui consequuntur accusantium culpa
                voluptatem hic amet animi?</p>
        </Card>
        <Card>
            <template v-slot:date>18 de mai, 2021</template>
            <template v-slot:title>Steam Deck rivals OneXPlayer, Aya, and GPD are planning their revenge with AMD’s
                6800U</template>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Officia autem iusto reprehenderit temporibus
                tempore laborum est ratione commodi molestiae? Aliquam excepturi a qui consequuntur accusantium culpa
                voluptatem hic amet animi?</p>
        </Card>
        <Card>
            <template v-slot:date>18 de mai, 2021</template>
            <template v-slot:title>How to check which version of Chrome OS you’re running</template>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Officia autem iusto reprehenderit temporibus
                tempore laborum est ratione commodi molestiae? Aliquam excepturi a qui consequuntur accusantium culpa
                voluptatem hic amet animi?</p>
        </Card>
        <Card like>
            <template v-slot:date>15 de abr, 2021</template>
            <template v-slot:title>Now non-Tesla EVs can use its Superchargers in the UK, Spain, Sweden, and
                Austria</template>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Officia autem iusto reprehenderit temporibus
                tempore laborum est ratione commodi molestiae? Aliquam excepturi a qui consequuntur accusantium culpa
                voluptatem hic amet animi?</p>
        </Card>
    </LayoutTheMain>
</template>